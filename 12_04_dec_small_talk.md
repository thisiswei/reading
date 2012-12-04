### Small talk by kent back -- Dhh say it's probably the best book in software..
----
naming 
> you want to include lots of information,you want it to be short,easy
to type and doesn't make formatting difficult,you want to communicate
why the variable exists,what type of the variable. 

----
###### name the variable after the role it plays

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

: Good programming style is one of those things that everyone knows when
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

