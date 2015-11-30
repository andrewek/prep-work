# More OOP

1. Learn and be able to define these terms (You don't need to know how to implement them yet):
    - Encapsulation
    - Message-passing
    - Abstraction
    - Inheritance
    - Composition
    - Polymorphism
    - Dependency Injection (How is this different from an options hash?)
    - Orthagonal Design
    - Duck-Typing
2. Go back to the [*n*-queens
problem](http://en.wikipedia.org/wiki/Eight_queens_puzzle). Create a `Board`
class which is responsible for keeping track of the board and placing queens.
Now create a `Queen` class which is responsible for keeping track of whether
or not it is threatened (the board will let it know whether or not it's
threatened). Note that the queens cannot see each other, and so depend on the
board for information.
3. Go back to your *Rock Paper Scissors* game. Create a class for players, a
subclass of the player class for AI players, a class for the game, and a class
for the referee. The game creates a referee and also a list of players (start
with just 2), then gives two players to the referee, who then has the
players battle. The winning player goes back into the player pool. The
losing player gets deleted (de-referenced, to be more precise). The game
keeps going until it has just one player left. Your players (human or AI)
should be able to generate (and pre-validate) their next move, which they
give to the referee (who then determines who won), and they should also be
able to keep track of their own game score, as well as total games won.
4. Object Oriented Design is mostly about splitting up responsibilities so
that any given piece of code can change without breaking anything else (it's
also useful for keeping track of "real-world" system, and for the way it
lets us re-use code). How might you split up the responsibilities between a
`Knight` class and a `Board` class in the Knight's tour? Try it out -- does
it work?
5. Do some reading into Object Oriented Programming. My favorite text
(though it's not free) is [*Practical Object Oriented Design in Ruby* by
Sandi Metz](http://www.poodr.com/). It's well worth the cost of the PDF,
though may be slightly above your current skill level (if so, wait for a few
weeks, and then try again. The barrier for entry here isn't too high, but it
does require some experience with OOP).

