# Data Saving and Error Handling
**Dev:** *Fanuel Santoso*

**Date:** *08.24.2022*

## Introduction
Hello everyone, today, in this paper today I am going to review what I studied in the seventh week of my programming camp. In this module I studied about saving data to data files and error handling. In this paper I’ll be splitting the materials into some parts for it to be understood easily. I’ll be explaining about what I studied, List, Dictionary, Function, Template, My Script, and finally the summary to summarize my paper.

## What I Studied
In todays’ module I watch the recording made by Mr. Randal Roots about Error handling and saving data with new commands.

## Data files
Today we learned 3 commands on this specific subject

The first one is written; this is where the command will put data that the user input has inputted or data that we told the command to write in the txt file. 

The second one is read; this command will make it so the program will open the targeted file and read the txt file. You can usually print it out with a for loop or the way the text is. 

The third one is append, this command does the same with write but it will not overwrite or delete the data that is already there. Instead of having only one data it will make two rows of data. From here u can print it out using read and for loops. 

## Pickled

Pickled are commands you can use that are not in python unless you call it in. In this case (Figure 4) it says import pickle to tell python to make specific commands that "pickle" have. The one I'm using is dump, this does the same thing with append but it has an easier command. This command will also make a txt file if the file doesn't exist before. Another is load where it will read the first row of data in multiple rows of data.

## Try – except

Try and except are two commands to make an alternative error message. Instead of saying something a user input wouldn't understand you can use try to try out your command first. If your command doesn't work, it will show them an error message that you can edit. XXX is a command that can contain errors.

## GitHub

We also learned some things about how to make a GitHub webpage like a professional. This means the GitHub raspatory is made well done. 

## My script

In my script here you can see that I made a simple script containing a choice where you can calculate two numbers. In this script the user input first will choose an option, if they pick option one, the user input will tell the program two numbers, this program then will write(save) the solutions of the two numbers in a txt file. I write it out using a pickle command (dump). The command will save the data with the exact list I made. This option can be chosen more than once.

If they pick option two, the program will read out all the lists that have been saved in the txt file from choice one.

If they pick option three, they will end the program.

In this script, I also added Try and Except commands. Because this script can contain errors depending on the user input. If the script doesn't have errors, it will continue normally and as expected. But if it has, 
The first error I expect is when the user chooses option two to start. Because the file hasn't been created (they haven't picked option one) it will show an error. Here it will print out an error message that can be understood by developers, but it will confuse the user input. Therefore, we can use except to change the error message saying, "file hasn't been created" and it will continue the while loop rather than ending the program. This will make the user input understand it better.
The second error I expect is when the second number is zero. Since you can't divide a number by zero it will show an error message. The error message will be different but can be understood by developers. Meanwhile, it will be hard for the user input to understand. Therefore, again we make a special sentence to show the user " Can't be divided by zero" rather than saying a complicated error message.

These are the function I have put to simplify my program.

Here you can see the result if I print the data saved in the txt file. 

## Summary
Thank you for reading my 7th paper about saving data and error handling. All of this can be done thanks to Mr. Randal Roots and Mr. Dave Blodgett for the videos. I hope the information given can be useful and can be understood easy. Thank you for reading
