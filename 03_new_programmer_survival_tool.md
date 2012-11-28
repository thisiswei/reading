### New Programmer's survival manual 

###### practices I can do :
  write a program that read lines of comma-separated data from a
 file,splits them apart,and use them to create object

  parse Xml file and save it.
   > It is very common task in industry,so it's useful to
   practice with loading and saving XML

     what happens when there are no item in the list? a blank field invalid characters
 
 > build some test for manipulating the customer list and save it back
 to file, you can use Builder for ruby 
  sukodu
   read a sudoku grid from a file,with some cells filled,some
   blank,solve it,print the result
   ( search easy sudoku) => (harder ones)


#####nov/28/2012 12:26pm

######style
>style refers to all things that a compiler don't care about but human
do

(naming of class,methods,variables,files,etc | arrangement of functions
within a file and cross files | comments | )

when naming:  their purpose => current|sum|previous| 

commentary :  /!-- this is a comment --/  
> code should be clear and tell what it does
instead,do this: 
   what parameters and return values expected
   TODO,FIXME  ( fix these before checking in)
   copyright,license
   match the style of anycode you're editing

###### Review code early and often
start the reivew by test
  nothing instills confidence in your code better than showing the tests
  my favorite question: 'let me see the test'. if the response is blank
stare, the review is over.
  doesn't have to be fancy,wicked--just solid code,make sure people see it
on regular basis

###### why?
>why choose this design

>what data you have can approve the assumptions

>how to prove or test that you implementation is correct

>how much wood could it chuck per second if it could chuck wood

> you use your development tool everyday,take a mental step back - the choice you made years ago may not be the best going forward

###### Tools
> mastery of at least one low-level and one high-level language will
give you tremendous flexibility

######balance your productivity with the machine's:
When trouble starts is when programmer think they need to write all
program small and fast. (computer's efficiency is less important than
yours) 
computers are cheap,programmer are expensive

> any program that is too slow, can't be fixed by adding more machine
> If the real-world use of the program could include huge data sets, you
design must account for that

-----------------
######nov/25/2012 


------------------------------------

######most important concept i receive is :

you must beat you code like a mutherfukcer before it get out of your door



> simplest way to assure code quality is to have another programmer read
it 

----------

######Acceptance Tests:
*when you got to withdraw money when the balance is 0, the screen print
out "what?You want some of this,bitch !"

###### Practices VS Mind-Set ----commit to solid code
> Testing gives you tool for both design and rigor at the same time.


> writing good test,just like writing good application,require
though,diligence,and good judgment.

######books mentioned: 
 * kent backs's Test-Driven-Development
 * The Rspec Book
 * kim Bruce's Foundations of Object-Oriented Languages
 * Growing Object-Oriented Software,Guided by test 
 * (The Rspec Book already mentioned twice)(i'll check
 [it](http://www.amazon.com/The-RSpec-Book-Behaviour-Development/dp/1934356379/ref=sr_1_1?ie=UTF8&qid=1353867587&sr=8-1&keywords=Rspec)
 out) 

 

###### start coding as soon as possible -- do it wrong first
>  I argue that whatever decision you make up front will be wrong  --
Scott 'Zz' Zimmerman

>  when I'm programming, I make a prototype with just a few big
classes,Then i write production code once i have a better piture of the
problem --- Scott 'Zz'

###### neccesary and accidental complexity
> the better opposite of complexity is clear (not simple)
> dig through you  project you working on and identify places where the
code could be clearer if that logic was abstracted into its own module

###### Line of Code is meature of weight,not progress


