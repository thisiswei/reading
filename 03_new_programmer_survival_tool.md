### New Programmer's survival manual 

##### practices I can do :
######write a program that read lines of comma-separated data from a file,splits them apart,and use them to create object

######parse Xml file and save it.
> It is very common task in industry,so it's useful to
   practice with loading and saving XML

what happens when there are no item in the list? a blank field ,invalid characters
 
> build some test for manipulating the customer list and save it back
 to file, you can use Builder for ruby 
 
#####sukodu
    
read a sudoku grid from a file,with some cells filled,some blank,solve it,print the result
    ( search easy sudoku) => (harder ones)
    
######books mentioned: 
 * kent backs's Test-Driven-Development
 * The Rspec Book
 * kim Bruce's Foundations of Object-Oriented Languages
 * Growing Object-Oriented Software,Guided by test 
 * (The Rspec Book already mentioned twice)(i'll check
 [it](http://www.amazon.com/The-RSpec-Book-Behaviour-Development/dp/1934356379/ref=sr_1_1?ie=UTF8&qid=1353867587&sr=8-1&keywords=Rspec) out) 
 * clean code

 
-----------------------

Dec/02/2012

> keep challenging yourself to make 10000 hours count

> start with simply doing your job well, then move onto getting noticed
> for it
 
> Good programmers are opinionated and strong-willed
 
> is there a part of the prodcut nobody else has experience in ?
> -- software packaging and field upgrade,it's a hairy mess,and nobody
> want to touch it. -- good place to dig in and learn
 
> Taking on Gnarly problem is how you build your expertise and credibility
> with in the team.
 
> sometime,you set out to tackle a problem,and it tackles you instead
 
> if stuck,pair pu with another programmer and try again,often a second
> set of fresh perspective are all it takes to make the brake through you
> need
 
 
> "Can i borrow some of Frank's time " ---ask manager
> 
 
> The only unacceptable pratice is floundering on you own, not asking for
> help. Recognize,when you've gone past the point of diminishing return
> and it's time to get another set of eyes on the problem.
 
> the easiest way to get in the middle of things is to physically get in
> the middle of things
> 
> Programming often requires intense concentration,and getting into that
> state--the flow or zone--takes time.
> 
> 
> The thoery behind meetings: decisions need to be made.
> 
> 
> you dont have to come up brilliant something,just steer the conversation
> toward solutions rather than griping about problems
> 
> change 'it sucks' to 'wouldn't it be cool if...',shift to creative
> mind-set
> 
> Brainstrom some short-term actions you could take to get closer to your
> goal.pick three and act on them over the next six months.
> 
> The overall goal of the marketing deparment is to influence people's
> perceptions about your company and the stuff it sells
> 
> Product management is about defining and marketing the things your
> company sells
> 
> waterfall : 
>     write a specification
>     write the code
>     test the code against the specification
>     ship it
> 
> this style works well when task are well-known and there isn't a lot of
> risk int the time estimates
> 
> Think about your most inspiring teacher,what was it about make them so
> great?
> 
> You need to run just to stand still

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


