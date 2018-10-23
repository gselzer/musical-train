# X-Team 15 Project Proposal: Pokemon Lite

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  

We want to create a simple Pokemon game to pick up childhood memories

Describe at a high level a program that could solve that problem.

We will design and implement a simple Pokemon game which only involves cathcing but not battles

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Pokemon Lite

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Pokemon appearance, type lookup, action prompt, ball choice prompt.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

We need a catch, run, or ball selection, represented by a button. Moreover, we need a list of pokemon to draw
pokemon from. 

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Welcome to the world of Pockemon
Press any key to encounter.

You encounter a pockemon **Name**

To check the property of **Name**, enter 0;

To catch it, enter 1;

To check what pockemon balls you have, enter 2;

to check the probability of catching it, enter 3; 
 
To look at the pockemons you have, enter 4;

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

* We need a class that stores data about the Pokemon encounter, i.e. the Pokemon we are encountering, the catch rate, and the dialogue.
* We need a Data Type that stores relevant Pokemon information.
* We need a Data Type (specialized HashTable?) that stores all of the Pokemon that can be encountered. This data type can be reused to log all of the Pokemon that the user has encountered.

Name each interface or class and briefly describe its function or purpose.

	Class Encounter {}
	Class Odds {}

## Edit and Submit this file and any figures referenced by this document.

