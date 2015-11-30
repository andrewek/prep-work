# Basics of Output

1. Write a program that prints "Hello World!" to the console.
2. Write a program that prints "Hello" and "World" to the screen, both on their own lines, and
each with their own `puts` statement.
3. Do the same as the previous problem, but with only one `print` statement (Hint: Use `\n`).
4. Figure out what the different [escape
sequences](http://en.wikibooks.org/wiki/Ruby_Programming/Strings#Escape_sequences) do. Do escape
sequences work the same regardless of if strings are single or double-quoted? For example: would
`puts "Hello\nWorld"` output the same as `puts 'Hello\nWorld'`?
5. Use String interpolation to do output. Do this with numbers and text. Does it matter whether
you do string interpolation with a double-quoted string (like `"#{1 + 1}"`) versus single-quoted
strings (like `'#{1 + 1}'`)?
6. (Advanced) Use [format
sequences](http://will-bloggs-too.com/2013/12/01/ruby-format-sequence/) (like `%s`) to do some
output. Does it work with double quoted strings? With single quoted strings?
7. What happens if you use string concatenation, i.e. `puts "hel" + "lo"`? What does
"concatenation" mean?
8. What happens if you try to multiply a string, i.e. `puts "Hello " * 3`. Can you divide a
string, e.g. `"hello" / "world"`? Can you subtract, e.g. `"Hello" - "lo"`?

