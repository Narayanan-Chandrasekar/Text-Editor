# Text-Editor
Multi Level Undo and Redo and Search feature notes

We can have 2 stacks for undo and redo commands.


While executing the commands we can push the commands in the undo stack 
When undoing the most recent command, pop out the command from the undo stack and push it on to the redo stack. Same case if the user wants to undo n number of commands

When redoing the most recent command, pop out  the command from the redo stack and push it onto the undo stack. Same case if the user wants to redo n number of commands.

For search functionality, we can implement the KMP algorithm.