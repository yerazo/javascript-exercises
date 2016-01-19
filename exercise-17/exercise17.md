==== EXERCISE 17: WORD COUNTING ====

1. Write a function `countWords` that accepts two arguments `sentence` and `word`.

2. Have your function return the total times a word is mentioned in the `sentence` argument.

3. Write a test case to make sure your function is working!

Super Hint: Use String.split() [http://mdn.io/split] to convert your sentence into an array of words.

Example usages of your function:

  countWords('How much wood would a woodchuck chuck?', 'wood') outputs 1

  countWords('A woodchuck would chuck as much wood as a woodchuck could chuck if a woodchuck could chuck wood.', 'chuck') outputs 3

4. As it stands, your function is likely case sensitive. How might you add another argument to control that behavior?

5. Your function won't account for words mixed into other words. For example, "woodchuck" contains both wood and chuck. How might you account for this? Your function shouldn't be able to handle "woodwoodwood" but it should be able to handle "woodchuck."
