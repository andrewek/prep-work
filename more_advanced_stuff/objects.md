# Objects and Classes

Objects and classes form the foundation of *Object Oriented Programming* (OOP), which is the
predominant paradigm for Ruby, but only one of several major paradigms (structural, declarative,
imperative, and functional are also all paradigms, to name a few). Most web applications do not
require too much OOP heavy lifting, but there are several problems that you'll run into that are
much easier to solve if you have a solid foundation of OOP.

1. Learn the definition of a **class** in Ruby. Learn the definition of an **object** in Ruby.
2. Learn the difference between **attribute** and **class** variables.
3. Learn the difference between **state** and **behavior** (with regard to Object Oriented
Programming).
4. Create a `Dog` class -- dogs should have names, ages, breeds, and should be able to `bark`
(`#{name} says "WOOF"`) and `walk` (`#{name} walks around`). Create getter and setter methods
for the attributes. When you create your Dog objects, you'll have to manually set the name, age,
and breed of each one.
5. Within the `Dog` class, create an `initialize` method which takes the name, age, and breed
as parameters, and which then sets the corresponding attribute variables to the passed in
parameters.
6. Learn how to use `attr_accessor`, `attr_reader`, and `attr_writer`. What are they used for?
Why would you use one instead of the other? Add an `attr_accessor` to your `Dog` class, and
get rid of the getter and setter methods you've set.
7. Now that you've got your objects, create an array of them. Use `.each` to iterate over the
array of dogs and have each dog bark.
8. Create a hash of Dog objects. The key should be the dog's name, and the value for each key
should the dog with that name. Can you use your previously created array of dogs, plus the
`.each` method, to automatically create this hash?
9. Create an array of dogs (who have various ages); iterate over this array (using `.each` and
a block), and print out the names of all dogs who are less than 5 years old.
10. Go back to your Rock Paper Scissors game -- re-create this game (with two human players)
using a `Player` class which has `name` and `score` attributes, and which can generate moves.
Create a `Game` script (this doesn't need to be in a class, but it can be), and have that game
create 2 players, set their names and scores, and have those players battle.
11. Research UML Class Diagrams. It's not important that you use these or adhere to them, but
they're a sometimes useful tool.

