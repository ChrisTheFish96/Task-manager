# Task-manager

## Description
A program with a login portion to manage a team's tasks within an organization. 
Different menus for admin and employee use.
The program helps with task sub setting and user task completion tracking.

## Table of Contents
1. Installation
1. Usage
1. Credits

## Installation
The code can be copied into any code editor.
Comments are available in the code to explain what each section does.

The user would also need the two text files in the same directory as the code in order to access it for user registration and task saving as the program runs.

User can use username "admin" and password "adm1n" to access all sections of the program, as a different menu is given to non-administrative users.

## Usage
Users first need to log into program with details as described above. 
![login_admin_menu](https://user-images.githubusercontent.com/125367266/226473434-2b8bb57f-dd4b-498f-8762-67a35bfca4dc.JPG)

This gives the user access to the admin menu with options to:
* Register a user
    * The user will be asked for a username and password and to confirm the password, if passwords match, the username and password will be saved to the user.txt file and can be used for login. 
    * If passwords don't match or the username already exists a relevant error message is printed.

![register_user](https://user-images.githubusercontent.com/125367266/226473475-cc955f35-0b07-4bdc-995d-4ffbfb7b40df.JPG)

* Add new tasks
   * User will be asked which user they want to assign the task to.
   * Then they must specify a name and description for the task as well as a due date.
   * If the user doesn't exist a relevant error message is printed

![add_tasks](https://user-images.githubusercontent.com/125367266/226473493-0ce29cba-a37b-40e0-99c8-0303818efa6e.JPG)

* View all the tasks registered to all users
   * All tasks on the system are printed out in an easy to read format.

![all_tasks](https://user-images.githubusercontent.com/125367266/226473544-76ff961b-b348-49ea-b08a-47314bcf9051.JPG)

* View all tasks given to the admin user
    * All tasks from the logged in user is displayed in an easy-to-read format
    * Users can then edit a task of their choice - they can edit the person it is assigned to,
    update the due date or mark it as complete
    
![my tasks](https://user-images.githubusercontent.com/125367266/226473585-9a50081a-7703-4585-8a6a-59dd574a999c.JPG)

* Generate reports
    * Creates a .txt file called user_overview
    * This provides the user with statistics of each user registered on the system.
    * Provides the number of tasks assigned to the user, how many of these are complete and incomplete as well as percentages of each. There are also the number overdue tasks as well as a percentage of these.

![user_overview_file](https://user-images.githubusercontent.com/125367266/226473610-7c89cec6-712f-4388-8842-14d300a674b5.JPG)

* Display statistics
    * This provides the same data from generate reports but it does not create a .txt file, it just prints the information to the terminal for easy access
    * Also provides an overview with all tasks on the system, number of complete, incomplete and 
    overdue tasks as well as the percentage of each.
    
![statistics](https://user-images.githubusercontent.com/125367266/226473651-7d2b3515-5a0c-4c6a-b7e8-55c04a3454f6.JPG)

If the logged in user is not an admin, they receive a smaller menu consisting of only:
* Adding tasks
* Viewing all tasks
* Viewing their own tasks

![non_admin_menu](https://user-images.githubusercontent.com/125367266/226473682-9dedcedc-70af-4424-a24a-6d21abc40779.JPG)

## Credits
This project was created by Christopher Barnard (ChrisTheFish96)
