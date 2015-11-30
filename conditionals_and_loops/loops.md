# Loops

When writing loops, consider finding ways to diagram the loop logic or to otherwise organize
your thinking. Loops are complicated.

1. Write a program that uses a loop (any type) to count from 1 to 10 on-screen.
2. Write a program that uses a loop (any type) to count down from 10 to 1 on-screen.
3. Write a program that counts from 1 to 100 by 2's. Now make it work by 3's. Now have it count
from 1 to 100 by any (positive) increment the user desires.
4. Learn how to use ranges (both inclusive and exclusive) to do numeric iteration.
5. Write a program which prompts the user for a positive odd number, and which keeps prompting
the user until they successfully input such a number.
6. Implement the [Collatz Conjecture](http://en.wikipedia.org/wiki/Collatz_conjecture). Print
out each step of the process, and keep track of how many steps it takes to arrive at 1.
7. Write a program which prints the integer factors of a positive integer (for example, the
integer factors of 28 are 1, 2, 4, 7, 14, and 28).
8. Write a program which, for any positive integer n, figures out n!. For example, 7! is 7 * 6 *
5 * 4 * 3 * 2 * 1.
9. Write a program which asks the user to enter a "password" (hardcoded in the code itself).
After three unsuccessful tries, the program should exit.
10. Write a program which displays the n<sup>th</sup> Fibonacci term to the screen. For the
purpose of this program, the first five Fibonacci terms are 0, 1, 1, 2, 3.
11. Write a program which prompts the user for a string of text and then prints that string out
vertically, i.e. one character per line.
12. Go back to your date validator you wrote in step 12 of the previous step; write a program
which prompts the user for a valid date, and then keeps prompting them until they divulge that
date.
13. Write a program which takes a multi-digit positive integer and which adds those digits
together, again and again, until it arrives at a number between 1 and 9. For example: `12345 >>
1 + 2 + 3 + 4 + 5 >> 15 >> 1 + 5 >> 6`
14. A number is divisible by 3 if the sum of its digits is a multiple of 3 (this process can be
repeated as many times as you like). Write a program which prompts the user for a positive
integer, then sum the digits of that integer (repeatedly, if necessary) until you end up with a
1-digit number; if that number is a 3, 6, or 9, you have a multiple of 3. Otherwise, you do not.
Verify your work with the `%` operator.
18. Use a nested loop (loops inside of loops) structure to create a multiplication table.
19. Use your Rock-Paper-Scissors program from the previous collection of exercises and re-write
it so that there is a best of 3.
15. Implement the [divisibility by 7 check](http://www.aaamath.com/div66_x7.htm). Check your
work by using the `%` operator.
16. Implement the [Luhn Algorithm](http://en.wikipedia.org/wiki/Luhn_algorithm). Test it against
your own credit card number.
17. (Advanced) Implement the Taylor Series out to 7 terms for `sin(x)` and `cos(x)`. Compare
this with `Math.sin()` and `Math.cos()`. Even if you haven't taken Calculus II, this problem
should still be approachable, though may require some extra work (as a hint, look up the Taylor
Series and implement it rote, instead of deriving it by hand). For fun, see how many terms you
have to go out to before the rounding error is less than 0.001.

Problems 1-3 are useful for learning new loop structures. You should be able to do each them
with a `while` loop, an `until` loop, with a range and `.each`, and with a `for` loop. What are
the relative strengths and weaknesses of each type of loop? Which ones are easiest to use?

(In our professional development, we use `.each` when iterating over an array or a hash, and
`while` for everything else. It's rare that we'll use `until` and *very* rare that we'll use a
`for` loop)

