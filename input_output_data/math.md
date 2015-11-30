# Simple Data Manipulation

1. Learn about Ruby operator precedence with regard to arithmetic. How does it
compare to the Order of Operations (PEMDAS) you learned in school? Learn what
each of the operators (listed below) does, then write a program that asks the
user for two numbers, then outputs the result of each of these operators on
those numbers. Make sure you can describe, in your own words, what each
operator does.
  - `+`
  - `-`
  - `/`
  - `*`
  - `%`
  - `**`
  - `=`
  - `==`
  - `<`, `>`, `<=`, `>=`
  - `<=>`
2. Write a program that fetches a number from the user, then doubles it, then
outputs the result. Write a program that fetches a number from the user,
squares it, then outputs the result.
3. Write a program that prompts the user for two integers, then displays the
integer quotient and integer result to the screen, like so: `7 / 3 = 2 r 1`.
Consider using string interpolation to make your life easier.
4. Write a program that converts a mixed number (integer, numerator,
denominator) into an improper fraction, e.g. `3 1/2 = 7/2`. This problem is
much easier if, instead of dealing with the fraction as a whole, you handle its
numerator and denominator separately.
4. Write a program that takes a floating-point value (like **1.75**) and
returns it as a fraction (like **7/4**). Hint: look in Ruby's [Float Class
Documentation](http://www.ruby-doc.org/core-2.1.2/Float.html).
5. Write a program that takes a string, then uses the `.upcase` method to
return the UPPERCASED version of that string, e.g. `"Hello".upcase => "HELLO"`.
6. Write a program that collects an integer value for Fahrenheit temperature
and then outputs the corresponding Celsius temperature.
7. Write a program that calculates how to break a monetary value (expressed as
`43.21`, that is, without the dollar sign) into the simplest possible change
(expressed as dollars, quarters, dimes, nickels, and pennies). "Simplest"
change just means the fewest number of bills and coins possible for a given
amount. As a hint, you'll need to use `%` and `/`. It may also be easiest to
convert the money amount from being in terms of dollars to being in terms of
pennies (for example, $43.21 is 4321 pennies).
8. Implement the Pythagorean Theorem; prompt the user for two integers *a* and
*b*, then find and output the corresponding value of *c* such that
**a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>**. You'll need to use
`Math.sqrt()` to find the value of *c*. Learn how to use [`Math.hypot`
method](http://www.ruby-doc.org/core-2.1.2/Math.html#method-c-hypot) and
compare your answers between the two ways of solving the problem.
9. Implement the distance formula: given two points, **(x<sub>1</sub>,
y<sub>1</sub>)** and **(x<sub>2</sub>, y<sub>2</sub>)**, find the distance
between those points. (Hint: this is a just a special case of the Pythagorean
Theorem). Solve it the long way, then solve it using `Math.hypot`.
10. Write a program which prompts the user for the month, date, and year
(four-digit) of a date (e.g. `7 / 28 / 2014`, though consider prompting the
user for the numeric month, numeric date, and numeric year separately if that
makes your life easier), and then implement [Zeller's
Congruence](http://en.wikipedia.org/wiki/Zeller%27s_congruence) to determine
the day of the week per the Gregorian Calendar. Your output should be an
integer between 0 and 6 (inclusive).
11. Write a program that collects a 4-digit integer from the user, then prints
that integer back out with its digits separated by spaces (i.e. `4321` becomes
`4 3 2 1`). Hint: you'll need to use the `%` (modulus) operator to split the
digits apart.
12. Write a program which prompts the user for miles driven and gallons of gas
used, and which then outputs full efficiency (in miles per gallon).
13. Write a program which prompts the user for distance traveled (miles) and
time traveled (hours), and which then outputs the average speed.
14. Write a program which prompts the user for two points (expressed as an
**(x, y)** ordered pair), and which calculates the slope of the line between
those points.
15. Research the [Float class](http://www.ruby-doc.org/core-2.1.2/Float.html)'s
`floor` and `ceil` methods. What do these do?
16. Learn how to use the compound assignment operators. What do they do?
  - `+=`
  - `-=`
  - `*=`
  - `/=`
  - `%=`
  - `**=`
  - `||=`
17. Write a program which prompts the user for the A, B, and C coefficients of
a quadratic function, and which then puts those into the Quadratic Formula and
outputs the two roots of that quadratic function. You'll need to learn how to
use `Math.sqrt`. This problem is easier if break the actual quadratic formula
into several steps, rather than trying to accomplish everything at once (use
your knowledge of the Order of Operations!).
18. Write a program which swaps the value of two variables using a swap variable.
19. (Advanced) Write a program which swaps the value of two integer variables
*without* using a swap variable. (This is a common interview question -- as a
hint, it involves nothing more than addition and subtraction).
