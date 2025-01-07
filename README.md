# Quiz-Game
It presents the user 
with a menu to start the game, view instructions, or exit. The game 
consists of three levels: easy, medium, and hard. Each level has five 
questions, and the user's score is calculated based on the number of 
correct answers. We can choose any function by using function calls which 
are declared in switch-case. In order to check the answer choosen for the 
question is correct or wrong, if else conditional statement is used. The 
application asks the person who runs the program to select a choice from 
given options. 
Here's an overview of the program's structure:
# 1.Read/Input
The program starts with the main function. It displays a welcome 
message and prompts the user to enter 1 to access the menu or 0 to exit.
If the user enters 1, the menu function is called, which presents the user 
with options to start the game or view instructions.
# 2.Selecting
If the user selects the start option, the start function is called. It prompts 
the user to enter their name and choose a level (easy, medium, or hard). 
Depending on the level chosen, the corresponding function (easy, 
medium, or hard) is called.
Each level function presents five questions to the user and checks the 
user's answers. The score is calculated based on the number of correct 
answers and deducted for incorrect answers.
# 3.Print
After answering all the questions, the user's score is displayed, and the 
rating function is called to provide rating based on the score.
Finally, a thank you message is displayed, and the program terminates.
