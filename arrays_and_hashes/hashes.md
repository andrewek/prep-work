# Hashes

Many of these problems will require you to access [Ruby's Hash
class](http://www.ruby-doc.org/core-2.1.2/Hash.html) core documentation.

1. What are hashes used for? Why might you use a hash?
2. Learn how to create a Hash that contains at least one key/value pair. What is the difference
between a key and a value? What types of data can be used as keys? Can you have duplicate keys
in a hash? What about duplicate values? What types of data can be used as values? Given a key,
how do you access the corresponding value in the hash? Given a value, how do you look up the
keys that have that value? How would you add additional keys to the hash?
3. Simulate a dictionary with a hash -- the key should be the word, and the value should be the
definition. Write a program which takes a word from the user and prints the corresponding
definition (if one exists in your dictionary) to the screen. If no definition exists (how would
you tell if this is the case), it should tell the user "Sorry, no definition exists" (or
something like that).
4. Learn what [symbols](http://rubylearning.com/satishtalim/ruby_symbols.html) are (and how
they're different from Strings). Create a hash which uses at least two symbols as keys, and
where each key has a value. Learn how to convert between strings and symbols.
5. What is the difference between an array and a hash? Why might you use an array instead of a
hash? Why might you use a hash instead of an array?
6. Hashes are often used to represent attributes that do not have corresponding behaviors (i.e.
the data doesn't *do* anything). For example, I could create a **Driver's License** hash that
contains a `:name`, `:id`, and `:age` key. Adjust the values to match your own information (or
information corresponding to someone whom you just made up).
7. Modify your Rock-Paper-Scissors game so that instead of using `if` / `elsif` / `else` blocks
to determine the winner, it instead uses a hash as a referee. First create a hash which has
"rock", "paper", and "scissors" as keys, and the *moves they win again* as the corresponding
values. Treat player 1's move as the key, and then check to see if Player 2's move matches the
corresponding value.
8. Learn how to iterate through a hash using key/value pairs -- at least initially, use a
`for-each`-style loop to iterate through a hash and print each key/value pair to the console.
9. Learn how to use the `.keys` method to get an array full of the possible keys in a hash.
Learn how to use the `.values` method to get the values in a hash.
