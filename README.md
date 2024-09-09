Task CLI Application

This is a relatively simple standalone text-based application written in Python intended to help you manage your work tasks as well as your ‘to-do’ lists. It provides the options to add, edit, remove tasks and change the status of the tasks from the command line.

Features:
Add a task
Edit a task
Remove a task
Change the status of a task to in-progress / done

Get a list of all tasks or tasks filtered by status

Getting Started
To install and run the Task CLI application, read the following instruction carefully.
Prerequisites
Python 3.x should be installed in your system
Familiarity with command line is an advantage
Setup Instructions
Clone the Repository / Download the Code:
Clone this repository or download the code with a zip file basicui into a folder which will be on your local computer.
Get into the Project Directory:
Now, type in your terminal or command prompt the location of the task1.py you had saved .

cd path/to/your/project-directory

Commands:
  python task1.py add "Buy groceries"
  python task1.py update 1 "Buy groceries and cook dinner"
  python task1.py delete 1
  python task1.py mark-in-progress 1
  python task1.py mark-done 1
  python task1.py list
  python task1.py list done
  python task1.py list in-progress
  python task1.py list todo

The project is for https://roadmap.sh/projects/task-tracker
