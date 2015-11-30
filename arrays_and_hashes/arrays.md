# Array Basics

Some of these questions will require you to refer to the [Array class core
documentation](http://www.ruby-doc.org/core-2.1.2/Array.html).

1. Create an array that holds a variety of data (Strings, integers, floats,
booleans). Print that array to the screen.
2. Create an array. Prompt the user for an index, then print the array element
at that index. What happens if the user tries to access a non-existent array
element? What happens if the user tries to use a floating point number or a
word as the index?
3. Learn how to use the `.length` to determine how many elements are in an
array.
4. Use a `while` loop to iterate through an array, printing each element to the
screen on its own line.
5. What is the difference between printing an array to the console with `puts`
as opposed to using `p`? Why might you use one instead of the other?
6. Learn how to use `<<` to add elements to an array.
7. Learn how to use `.push` and `.pop` with arrays. What do each of these do?
8. What happens if you declare the array size without filling it with elements,
i.e. if you do something like `a = Array.new(5)`? What's in the array?
9. Write a program which prompts the user for a number, and which then stores
the positive integer factors of that number in an array. For extra credit,
iterate over this array, starting with the first factor greater than 1, and
remove any factors that are divisible by that factor. At this point, you should
have a list of prime factors of a number.
10. Two numbers are *co-prime* if and only if they share no common prime
factors (remember that 1 is not a prime number); for example, even though
neither 81 nor 125 are prime numbers, they share no common prime factors and
thus can be considered to be co-prime. Modify the program you wrote in the
previous step to determine if two numbers (supplied by the user) are co-prime.
11. Imagine that you have a hallway which has 500 switches, and that each
switch has a corresponding bulb right next to it. All the switches start in the
"off" position. You start at switch #1 and count up by 1's, flipping every
switch until you get to the end. Then you come back to the beginning, and
repeat the process starting at switch #2 and flipping every second switch (and
so on until you are all the way done with the hallway). By the time you start
with the 500<sup>th</sup> switch, thus completing the process, which switches
are on, and which ones are off? Use an array with 501 elements to simulate this
hallway (ignore element 0), as well as a nested loop structure to simulate this
problem. As a hint, it may be easiest to simulate the switches as booleans,
though you can use strings, symbols, integers, or any of a number of other
methods. With the switches that are on, what common numeric property makes
those the ones that are left on?
12. Learn how to create a multi-dimensional array. Learn how to access elements
within the multidimensional array.
13. Re-implement the Fibonacci sequence, but this time do it with an array;
each array element will be the sum of the previous two elements. Remember that
the 0<sup>th</sup> Fibonacci term is 0, and the 1<sup>st</sup> Fibonacci term
is 1.
14. Implement the [Rational Roots
Theorem](http://en.wikipedia.org/wiki/Rational_root_theorem); store your
polynomial in an array of its coeffiecients. For example, **5x<sup>4</sup> -
3x<sup>3</sup> + 2x - 3** would be represented as `[5, -3, 0, 2, -3]` (since
there is no x<sup>2</sup> term, the coefficient there is 0). Then store your
*p* and *q* values each in their own array before testing each combination of
values. Consider creating an array for all of the **p / q** values, then use
the [Array class's `.uniq!`
method](http://www.ruby-doc.org/core-2.1.2/Array.html#method-i-uniq) to
eliminate all duplicates. Make sure your **p / q** array is full of floats,
rather than full of rounded integers.
15. Use the [solutions heuristic for the *n*-Queens
Problem](http://en.wikipedia.org/wiki/Eight_queens_puzzle#Solution_construction)
to generate solutions for any user-generated value of *n* greater than or equal
to 4. This program is probably easier with a two-dimensional **n** by **n**
array. Output the results and test manually.
16. Write a program which prompts the user for a 3x3 grid of numbers; test to
see if this grid fulfills the properties of a [Magic
Square](http://en.wikipedia.org/wiki/Magic_square).
17. Use the Array's `.sample` method to randomly select an element from the
array.
18. Use the Array's `.sample` method to simulate an AI in Rock-Paper-Scissors
(hint: create an array of possible opponent moves). You'll need to build out
the rest of the Rock-Paper-Scissors game as well.
19. (Advanced) Implement [Conway's Game of
Life](http://en.wikipedia.org/wiki/Conway's_Game_of_Life). Use a
two-dimensional array full of `true` and `false` values to represent the grid
itself (`true` means the cell is alive; `false` means it is not). Initially,
you'll probably want the user to signal the next step in the iteration by some
nominal input, but eventually you can have the user specify a number of
iterations and have the program complete those automatically.
20. Create an 8x8 multidimensional array (representing a chessboard), then
create a piece which can move like the King can (i.e. 1 square in any
direction). Make sure to write logic which keeps the king from moving off the
board entirely. When you are done with this, re-write the program using a
single dimensional array with 64 spots; you may need to label the squares of a
chess board from 0 to 63. See if you can accomplish the same task.
21. (Advanced) Implement the [Knight's
Tour](http://en.wikipedia.org/wiki/Knight's_tour) using a brute force method.
Your program will probably not complete any successful tours of all 64 squares,
but it should reliably get to at least 10 moves. Represent the chessboard as a
boolean array, with cells marked as `false` if they have not yet been visited
and `true` if they have. For each next step, generate a list of available
squares that are in range of the current square, and then select one at random.
This program can be done with a 1-dimensional array (i.e. with squares labeled
from 0 to 63), though is more frequently done with a 2-dimensional array simply
because the grid-analog is easier to understand there. Consider storing the
generated tour as an array, then outputting it to the screen. Use the array's
`.length` attribute to see how long the tour is.
    - HINT: Recall that arrays in Ruby can hold any value and any combination
      of values. Thus, you may wish to represent the knight as a **K** while    
      representing the rest of the board as true/false values -- any time the
      knight leaves a space, that space turns to `true` and the space the knight is
      on turns from `false` to **K**.
22. (Advanced) Build on the Knight's Tour by implementing [Warnsdorff's
Rule](http://en.wikipedia.org/wiki/Knight's_tour#Warnsdorff.27s_rule). Create a
second array (full of integers) that mirrors your first array, except that
instead of listing the cells, it lists how many available moves there are from
that cell. See how long it takes for your program to find a successful tour.

