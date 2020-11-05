# CLASS 10 READING NOTES

- [Home](https://seidomo.github.io/201-reading-notes/home) 

# DEBUGGING

- JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully. 

- When you are writing JavaScript, do not expect to write it perfectly the first time.
Programming is like problem solving: you are given a puzzle and not only do you have to solve
it, but you also need to create the instructions that allow the computer to solve it. too. 

- When writing a long script, nobody gets everything right in their first attempt. The error
messages that a browser gives look cryptic at first, but they can help you determine what
went wrong in your JavaScript and how to fix it. In this chapter you will learn about: 

- THE CONSOLE & DEV TOOLS
Tools built into the browser that help you hunt for errors.

- COMMON PROBLEMS
Common sources of errors, and how to solve them.

- HANDLING ERRORS
How code can deal with potential errors gracefully. 

## ORDER OF EXECUTION 

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run.

## EXECUTION CONTEXTS 

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

## EXECUTION CONTEXT & HOISTING 

Each time a script enters a new execution context, there are two phases
of activity: 
- PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined 

- EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements 

## UNDERSTANDING SCOPE

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 

## HOW TO DEAL WITH ERRORS 

Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors. 

- DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.

- HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and finally statements. 

## A DEBUGGING WORKFLOW

Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues.

## WRITING FROM THE SCRIPT TO THE CONSOLE 

Browsers that have a console have a console object, which has several
methods that your script can use to display data in the console.
The object is documented in the Console API. 

 ## BREAKPOINTS

 You can pause the execution of a script on any
line using breakpoints. Then you can check the
values stored in variables at that point in time. 

## CONDITIONAL BREAKPOINTS 

You can indicate that a breakpoint should be
triggered only if a condition that you specify is
met. The condition can use existing variables. 

## DEBUGGING TIPS 

- ANOTHER BROWSER
Some problems are browserspecific. Try the code in another
browser to see which ones are causing a problem.
- ADD NUMBERS
Write numbers to the console
so you can see which the items
get logged. It shows how far your
code runs before errors stop it.
- STRIP IT BACK
Remove parts of code, and strip
it down to the minimum you
need. You can do this either by
removing the code altogether, or
by just commenting it out using
- EXPLAINING THE CODE
Programmers often report
finding a solution to a problem
while explaining the code to
someone else. 
- SEARCH
Stack Overflow is a Q+A site for programmers.
Or use a traditional search engine such as Google,
 Bing, or DuckDuckGo.
- CODE PLAYGROUNDS
If you want to ask about
problematic code on a forum, in
addition to pasting the code into
a post, you could add it to a code
playground site (such as
JSBin.com, JSFiddle. com, or
Dabbl et. corn) and then post a
link to it from the forum.
- VALIDATION TOOLS
There are a number of on line
validation tools that can help you
try to find errors in your code: 


- [Previous](https://seidomo.github.io/201-reading-notes/class09) 
