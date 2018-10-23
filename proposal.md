# X-Team 55: Degrees of Separation

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
Ancestry Tree. Will hold birth, death, relationship data.
Describe at a high level a program that could solve that problem.

# How many contacts does John need to go through to get in touch with Sarah?
This problem creates a graph from individuals and their contact lists. A question we would like to answer what is the least number of contacts a specified person would need to go through to get in touch with someone else, if that is even possible. The way we would solve it is traversing through the graph in a depth first manner until that person is found, then optimizing until the least number of contact touches is determined.


## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Degrees of Separation


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
When requested, the program will output data on a person's relationship with an other person's in the graph.
Requesting data on John Doe and Mary Jane...
John Doe - 4 relationships close to Mary Jane... <John Doe - Person - Person - Person - Mary Jane>

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
First we would be needing the data to make each Node. Every Node will have the person's basic details like name and date of birth. Then we will need the connections between every person to establish the relationships between each person.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
A prompt will appear asking the user what to do. The prompt will be a simple text menu.
The user will have the choice of either searching the relationship of two people, or to add a person.
If search is chosen, the user will input two people.
If add a person is chosen, then the user will add the person and then that person's relationship to someone else.


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
There will be a Person Node that has a list of all known relationships. The node will store all the personal data of the person such as age, martial status, and birth date. There will also be a Main class that the user interacts with where they can input who they are and who they are trying to reach.


Name each interface or class and briefly describe its function or purpose.
Person class - Will be the node that will hold an individual's degree of separation, name, etc.
Graph class - Implements a graph to hold nodes.

## Edit and Submit this file and any figures referenced by this document.

