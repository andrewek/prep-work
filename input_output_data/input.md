# Getting Input and Using Variables

1. Learn what Strings, Integers, Floats (floating point numbers), Symbols, and
Booleans are. Learn what values they can store.
2. Create a variable called `name` and store your name in it. Print this to the
screen using `puts`, then do it again using string interpolation.
3. Create two variables and assign a number to each of them. Then create a
third variable and assign to it the sum of the first two. Print all three to
the screen like so: `3 + 7 = 10`.
4. Do the same as #3, but see what happens if one of the numbers is a floating
point number (e.g. `4.2`). What happens if both numbers are floating point
numbers?
5. Research the different truth values: `true`, `false`, and `nil`. What does
`nil` mean within Ruby?
6. Use `gets.chomp` to collect input from the user and store it in a variable.
Write a program that asks the user for their name, then print their name to the
screen. Write a program that asks the user for their age, and then print that
age to the screen.
7. `gets.chomp` collects input as Strings (text). Learn how to use
`gets.chomp.to_i` to collect integers, as well as `gets.chomp.to_f` to collect
floating point numbers. What happens if you try to call `gets.chomp.to_i` when
a floating point number is entered? How about when a word or letter is entered?
What happens if you use `gets.chomp.to_f` and input an integer? A word?
8. What is the difference between `puts 1 + 1` and `puts "1" + "1"`? Why does
this behavior happen?
