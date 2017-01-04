
<h1> Notecards, Notecards, Notecards! </h1>

## Synopsis
  
This is a basic program to test ability to remember terms/concepts, similar to how one would use notecards in which a term is written on one side and a definiton on the other. 

## Usage

To use the program, save the terms you wanted to be tested on in a text file in this format:

Term: Definition

Like such:

---------------{Insert Image HEERE}---------------------------

## Functionality
-- Reads in term/definition combinations from a file
-- Prints the full list lf of terms, and asks you if you want to delete any terms from the list 
-- Tells you how many terms there are
-- Asks you if you want to be timed
-- Shuffles the terms, then begins to test you:
-- Prints the term, then waits for you to proceed
-- Prints definition
-- Asks if you got it right (remembered the proper definition of the term)
-- If you did, then it deletes the term. Otherwise it keeps the term
-- Repeats this until it runs through all the terms, then prints how many terms are left and runs back through the terms
-- At the end, the time it took you to complete will be printed if you chose to be timed.  

## Hot Keys
When asked for user input, you can enter "Y", "y", or "'" and then hit the "enter" / "return" key to go forward. I personally prefer the "'" key because it is right next to the enter key. 

After a term has been printed, "--$--" will appear. To move forward here, simply hit "enter" when you are ready. 

## Features
-- Can be timed to see how long it takes to finish testing yourself
-- When asked "Did you get it right?", if you enter "time" it will tell you how long it has taken you at that point.
-- If you do not know a term, type "slow hint" to have the definition printed slowly and word-by-word. Hopefully this will help jog your memory!

## Drawbacks
1) There can only be one colon in per term/definition pair because the colon is what the program draws on as the split between term and definition. 

2) For each term, everything has to be inline in the original text file, meaning you can't read in bulleted lists or anything of that nature. 


## Author
Kody Fisher (<a href="https://twitter.com/kfish_15">@kfish_15</a>)

Would love to hear your comments or tips for improvement!




