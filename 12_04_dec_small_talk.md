### Small talk by kent back -- Dhh say it's probably the best book in software..

dec 05 8:38 am 
----
whole hog - read the patterns through once quickly. Then set the book on
you lap as you program.Everytime you about to do anything--write a
method,name a variable,look it up first

my experience with whole hog was that i spent couple of frustrating days
programming at less than full speed.After than,I memorized enough
patterns to get back up to my old productivity,but the code I was
producing was cleaner than before,after couple of week,I no longer had
to look up any pattern, and my productivity shot up while my code kept
getting cleaner and cleaner

why does this work? I think it is because when i use to program I would
constantly have to two parallel converstion going on in my head -- what
should i name this variable and how should I approach naming this
variable.When I chose to follow the patterns explicityly,the second
conversation disappeared and I had more attention to pay to the problem
I was solving.

----
Developers don't ever develop from scrath.Many problem recur in various
guises throughout development.Mature engineering disciplines capitalize
on the repetitive nature of development by collecting handbooks of
adequate solutions to recurring problems.A bridge designer designs using
the solution in the handbook, lik I-beams,not the laws of physics.


when we say 70% of the development budget is spent on maintenance
--- we mean that poor maintainers have to wade through piles of
documentation and code to discover the intent of the original programmer

----
when you want to improve communication,you have two choices,either
increase the bandwith so you can communicate more bits or increase the
context shared between sender and reciver so the same number of bits
mean more.

patterns are literary form for capturing and transmitting common
practice.Each pattern records a recurring problem,how to construct a
solutino for the problem,and why the solution is appropriate.

Expertise in development often hinges on knowing what problems should be
solved first and what can be safely ignored.

----

Behavior is the dynamic,active,computational part of the model,State is
what is left after behavior id done,how the model is represented
before,after,and during a computation.

Well,separating computation into messages and methods and binding
messages to the method at the runtime based on the class of receiver
many seem like a small change from an ordinary procedure call,but it's a
small change the makes big difference.

Method are how you communicate to readers how you intended for work to
get down.You must write you methods with both of these audiences in
mind.carefully choosing their names communicates more about your
intentions to a reader than any other programming decision besides class
naming.

Return a Boolean.Name the method by prefacing the property name with a
form of 'be',is,was,will,etc, 
      isNil,isEmpty

naming method: name them after what they accomplish.
the effort of moving the names of method from 'how' to 'what' is worth
it,both long term and short term,the resulting code will be easier and
flexiable


----
Any use of super reduces the flexibility of the resulting code

The choice of how to represent a model is the core of modeling,the
decision to create an instance variable usually comes from a much
different mind-set and in a different context than the decision to
create a temp.

functional programming -- where there is no state.only programs.
the problem is that we think, we model in terms of state.State is
pretty darn good way to think about the world.

----
name the variable using role suggesting instance variable name.

you should use an initialize method when you want people to read your
code as easily as possible.

When you write classes that only have a handful of methods,adding a
getting and setting method can easily double the number of methods in
your class.Twice as many methods to buy you flexibility that you never
use.

Here's the real secret of writing good getting methods: make them
private frist.

provide a method that returns the value of the variable.Give it same
name as the variable.

name instance variables for the role they play in the computation.make
the name plural if the variable will hold a collection.

----
naming 
> you want to include lots of information,you want it to be short,easy
to type and doesn't make formatting difficult,you want to communicate
why the variable exists,what type of the variable. 

----
##### name the variable after the role it plays

what is its purpose?
how is it used?

__First__ you figure out what you want the computer to do. Then you instruct
it to do it.

If you're programming along,doing nicely,all of a sudden you program
gets balky,makes things hard for you,it's talking.

Some of the biggest improvements come from figuring out how to
eliminate: Duplicate code (even little bit of it)
* conditional  logic
* complex methods
* stuctural code,where one object treats another as a data structure

In derivatives trading,a quickly shipped program is a good program.

Life-cycle cost -- if there is one driving force behind the patterns it
is the reduction of life-cycle costs of software.

Time to Market -- When pressure become intense to get the product to
market,it is tempting to cut corners.However, the very act of deciding
what corners to cut slows down the development.

 
----
####Style

:  Good programming style is one of those things that everyone knows when
they see it, but it is very hard to articulate precisely -- the good
programming style is one that make money,is objectively measureable but
hard to apply day to day.

* Once and only once
> If I only have one min to describe good style, I
reduce it to simple rule: in a program written with good style
everything is said once and only once. If I see several methods with the
same logic, or several systems with similar objects, I know this rule
isn't satisfied

* lots of little pieces
> Good code invaraiby has small methods and small objects. Only by
factoring the system into many small pieces of state and functions can
you hope to satisfy the "one and only once" rule.

* replacing objects
> Good style leads to easily replaceable objects. "I want to do
something different", when you can extend a system solely by adding new
objects without modifying any exists objects,then you have a flexiable
and cheap to maintain system.

* moving objects
> objects can be easily move to new contexts.You should never be able to
say," This object in this system does what that object in the system
does,but they can't be the same"

* rates of changes
> don't put two rates of change together.Don't have part of method that
change every superclass with parts that don't change. Don't have some
instance varaiable whose values changes every second in the same object
with whose value change once a month.Don't have a collection where some
element are added and removed every second and some elements are added
...once a month.Don't have code in an object that has to change for
every piece of hardware and code that has to change for every operating
system.

----

If you don't do what's needed,the client will not be satisfied with the
result.If you do what isn't needed, you add cost,time,and most
importantly risk to your project

Design interfaces that users find valuable is an art,Implementing them
simple,flexibly,and reusably is the test of solid SmallTalker.

