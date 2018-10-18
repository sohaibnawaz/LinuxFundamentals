# Linux Fundamentals

Linux assesment project.

## Introduction

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Script 1

Create a bash script that will do the following: Create a new directory within your current working directory and name it ‘QAC [your first name]’. Go into this new directory and create 3 new files. Use a text editor (nano, gedit, etc.) to add some text to one of these files, save and close. Create another directory within your QAC directory and name it ‘childDir’. Copy the file you created and edited into this new directory within the QAC directory. 

### Script 2

Once you have ran this script, you should have a number of files and directories created. Continuing from this, complete the following:

In your second file, write a script that will: Call a function that asks for a number, and prints whether it is odd or even. Print the result of the script to a file (i.e. the third file you created). There should be a question asked to the user as to whether they want to
delete the file. If they do, remove the third file. If they don’t, create/touch
the file. Change the name of this third file to ‘changedFileName’ and move it to the home directory. 

### Script 3

Write a script that will say take a user input for a username, and based on the username provided, will print out their user ID and the groups they are in.

### Script 4

Write a script that will list all active processes, then ask the user for a process ID. Based on the process ID provided, stop that process.

### Script 5

Create a script that will take any amount of user provided numbers. When the user decides they no longer want to enter any more numbers, print out a list of the numbers in order.

### Script 6

Create a script that implements an array, which will hold values from 1 to any given user number. From here, loop through all items in the array. If a number divides by 3, echo “Fizz!” instead of the number. If the number divides by 5, echo “Buzz!” instead of the number.

### Script 7 

Create a script that reports information on a user-provided name of a directory.
Things to report on include:
a. How many files are in the directory
b. When the directory was last edited
c. The largest/smallest file

### Script 8

Write a script that will print out all user ID’s and usernames from the relevant file, output them into a new file in your home directory, and delete any files that are not owned by your user or the root user. Format this script so that the output into the new file is in a nice format (separated by hyphens, comments, etc.)

### Script 9

There is a Java tar file on the LocalInstall of your host machine. Get this into your virtual machine and install Java onto your VM with the use of this file. Extend upon this by writing a script that automates the install with this file.

### Script 10

Write a script that will lock a file based on the name of the file provided by the user. Your script should ensure that the user provided name of the file is owned by the user running the script.
