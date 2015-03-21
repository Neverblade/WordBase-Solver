# WordBase-Solver
A solver for the mobile game WordBase that supplies the user with the best words they can use.


To use, input your game into the input.txt file and then compile and run WordBase.
Load a save by inputting the name of your game, and it'll output a list of good words based off of different criteria.

Input Structure:

     Input starts with a name of [game name] [your color] where color is either "O" for orange or "B" for blue.
     Then on the next line, input your game grid, with spaces between letters on a row.
     Skip a line, then input your territory grid, with 0 for your space, 1, for white space, 2 for opponent's space, and 3 for bombs.


Features:

     An input file to save and load multiple games off of.
     Adjustable list sizes.
     Supplies the list of best words to use based off of length, distance gained, etc.
     Specific tile targetting system to help cut-off the opponent.
     
     
What I learned:

     Recursion
     ArrayLists
     Reading files
     Sorting and searching data
     
     
Needs Work:

     Because this was written before I learned OOP, the structure is messy and inflexible.
     Eventually I need to rewrite this using objects.
     Need to upgrade with graphical representations/input.
     
