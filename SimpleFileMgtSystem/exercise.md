Exercise: Simple File Management System
Objective:
Create a Bash script that acts as a mini file management system. The script should perform various tasks based on user input, such as listing files, searching for files, modifying file permissions, and displaying file content.

Requirements:
Main Menu:
The script should display a menu with options like:

List directory contents
Search for a file
Create a new directory
Change to a different directory
Display the content of a file
Modify file permissions
Exit
Implement Functions:

Use functions for each menu option to keep the script modular and organized.
Conditions and Case Statements:

Use a case statement to handle user choices from the menu.
Loops:

Keep showing the menu in a loop until the user chooses to exit.
Variables:

Use variables to store user inputs like directory paths or file names.
Environment Variables:

Use an environment variable to store the default directory the script operates in (e.g., $HOME).
Error Handling:

If a user enters an invalid option or the specified file/directory does not exist, show an appropriate message.
File Permissions:

Allow the user to modify permissions of a file (e.g., make a file executable).
Example Workflow:
User Starts the Script:

The script shows the main menu.
User Chooses "Search for a File":

The script asks for the file name and searches for it in the current directory.
User Chooses "Modify File Permissions":

The script asks for the file name and permission mode (e.g., 755) and applies it.
User Chooses "Exit":

The script terminates.
