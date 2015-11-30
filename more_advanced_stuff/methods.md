# Methods

If you're not already comfortable with methods, it may be worthwhile to do some
research beforehand. [This
article](http://www.tutorialspoint.com/ruby/ruby_methods.htm) isn't a bad place
to start.

1. Learn how to create a method.
2. Learn the meanings of each of these terms regarding methods:
  - Method signature/name
  - Parameters
  - Arguments (how are parameters and arguments different?)
  - Method call
  - Return values
  - Method body
3. Create a method called `hello_world` which takes no arguments and which
prints `Hello, World` to the screen. Call this method.
4. Create a method called `greeting` which takes a single argument (a name) and
prints `Hello, #{name}` to the screen. Call this method with a few different
names.
5. Create a method called `sum_these_numbers` which takes two integers as
arguments and prints their sum to the screen.  
6. Modify `sum_these_numbers` (written before) so that instead of printing the
sum, it returns the sum back to where the method was called. Print the sum
(calculated by the method) to the screen, but don't do that printing inside of
the method.
7. Learn the difference between **implicit** and **explicit** returns in Ruby.
How do you return values without the `return` keyword?  
8. Create a method called `is_even`, which takes a single integer, and which
then returns `true` if the number is even, and `false` otherwise.
9. Read about the [Single Responsibility
Principle](http://en.wikipedia.org/wiki/Single_responsibility_principle). Be
able to define it in your own words, preferably in just 1-2 sentences.
Recognize that the difference between the two `sum_these_numbers` methods
(created in the previous two steps) is that one calculates the sum **and** does
output, whereas the other just calculates the sum. Which one better adheres to
the SRP?  
10. Write a method which calls another method, then uses its return
value.
11. Learn how to use the `yield` command (within methods), and then call a
method with a block. This is particularly useful for iterators. As you become a
better programmer, you'll find that knowing when to use this technique is a
matter of intuition and experience, rather than anything very prescribed.
12.  Look at problems from the previous steps, particularly ones where the
program takes some information, does some stuff, then comes back with a result.
Turn a few of these into methods. Almost all of the problems listed in the
previous sections can be re-written to use methods and to adhere to the single
responsibility principle. Go ahead and use multiple methods if necessary.
13. (Advanced) Do some research into recursive methods (methods which call
themselves). Research recursive solutions to the Fibonacci Sequence generator
(which you've seen already), and try implementing them. Recursive methods are
extremely useful for iterating over certain types of data structures, but they
won't be useful to you just yet.

