# Project One: Software Engineering and Design

## Batman: Cave of Injustice ##

This project is a text-based game named Batman: Cave of Injustice. This was a project developed in IT140, Intro to Scripting, three years ago, in July 2021. The application was developed using the PyCharm IDE and the Python coding language. I chose this project as my first to enhance because it reflects my growth over my time at SNHU. It demonstrates the importance of adhering to basic coding standards and organizing your code to be easily readable and maintainable. The initial structure of the code had each item and location in the game being tracked by their own int variable. The variable values were the opposite for each group. For example, an item obtained is essentially a ‘yes’ the item was obtained and a room location where you were was a ‘yes’ you are in this room. However, an item obtained was tracked with a 0 value while the room you were in was tracked with a 1. This system was confusing and introduced a lot of clutter. My original submission, three years ago, included a few issues like this one that allowed for a playable game but not an easily maintained game.

To correct this, one of the main enhancements made was the introduction of arrays and dictionaries. These data structures allowed me to showcase my ability to restructure code and solve the problem of clutter by introducing coding standards and greatly simplifying the code. Improved commenting further improved the maintainability of the program. 

![image](https://github.com/user-attachments/assets/3c451e02-29b3-463c-9fc3-00e6d309f377)

In addition to the coding standards that were enhanced, overall gameplay and mechanics were added to make the game more enjoyable. A displayable map was implemented so the player could track where they were in the game, rather than referring to an outside source. Similarly, a displayable item list was implemented to track items obtained, which is important because it is a win condition for the game. Lastly, difficulty levels were implemented to allow another level of gameplay and introduce more strategy to the game.

## Game Instructions ##

### Objective ###

Navigate through the batcave to collect your gadgets. Superman must be avoided until all 7 gadgets have been collected.

### Game Modes ####

Easy - Superman will stay in the Hangar and wait for you to face him.

Hard - Superman will wander randomly throughout the batcave.

###  Controls ###

User must enter one of the following in the prompt:

- 'I' = View a list of collected inventory.
- 'M' = View the map. The map will tell you each room that has an item as well as the locations of you and Superman.
- 'North' = Move to the room above.
- 'South' = Move to the room below.
- 'East' = Move to the room to the right.
- 'West' = Move to the room to the left.

Course Outcomes Displayed
---
### Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science. ###

Building a collaborative environment includes developing projects in such a way that they can be easily passed from one team to another for continued improvement. By removing unnecessary repetition and clutter, enhancing comments, and simplifying the code, my enhancements ensure easier collaboration. 

---
### Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices. ###

The implementation of arrays and dictionaries uses computer science best practices and standards to solve the problem of clutter, repetive code, and overcomplication. Even with the addition of new features, the code for the game is much shorter with these things in place.
