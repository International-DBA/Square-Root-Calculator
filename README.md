Nowadays it is easy to calculate square roots as most computer languages have a function to do this for you.
In 1974, long before I first saw a computer, I was shown a different method, which used an electronic calculator.
These were introduced in the early 1970's.
The PL/SQL function shown here demonstrates this method by calculating the square root of a number supplied as an input parameter.
First, it makes an arbitrary guess of 1, which goes in variable sr1.
Then it divides the number supplied by the square root, sr1, to calculate sr2.
The next step is to work out the mean or average of sr1 and sr2 and assign this back to sr1, making it a slightly better approximation.
Then it repeats the process.
After a few iterations, sr1 becomes a much better approximation to the square root.
To test the accuracy of the square root, it is multiplied by itself to see how close the result is to the original number.
Variable pcd calculates the difference between the original number and the square of its square root then expresses this as a percentage.
Processing continues until this is one millionth of a percent or less.
