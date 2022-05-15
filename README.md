# Tic-Tac-Toe
The objective of this Tic-Tac-Toe Game Python Project is to Build a Tic-Tac-Toe Game so you can play it without wasting paper and improve your concentration.To build this game we use the Tkinter module with the concept of python.
To play this game we require two players to play one is X and the other is O and both players play by putting their marks in empty squares.
To win the game players have to get 3 of her marks in a row (up, down, across, or diagonally).
To build tic-tac-toe game using python we require tkinter module and basic concept of python
Tkinter modules is a standard graphical user interface used to render graphics.
Tkinter.messagebox used to display message box
To install tkinter modules we used pip install command on command prompt.

These are the step to build Tic-Tac-Toe game using python :

1.Import modules
2.Initialize window
3.Function to check result
4.Function to check the winner
5.Define labels and buttons

2.Initialize window
->Tk() is use to initialize window
->title() used to set the title of the window

3.Function to check the result
->In this function, the result will be checked by checking which player makes three of their marks in a row (up, down, across, or diagonally).

4.Function to check the winner
->Players have a total of 9 clicks to play the game. Each time the player clicked, one chance will decrease
  by increasing the value of count by 1 if the value of count is greater than 8 then the result of game is tie.
->If the value of count is even then player1 will play else player2 will play.
->config() used to mark the button with appropriate text
->showinfo() methods in the messagebox widget used to show some relevant information
->destroy() stop the mainloop to quit the program

5. Define labels and buttons
-> Label() widget used to display text that users aren’t able to modify.
->Button() widget display button
->root is the name of window which we refered
->text stores the value which we display on the label
->font in which our text is written
->command will called when the button is clicked
->lambda() function used to send specific data to the callback function.

We have successfully devloped the Tic-Tac-Toe game project in python. We use tkinter module for rendering graphics on a display window.
We learn how to create buttons and config text on buttons and also how to use lambda functions to send specific values to callback functions.
In this way we successfully made a Tic-Tac-Toe game python project. I hope you enjoyed building tic-tac-toe game project.
