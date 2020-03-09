# Interview Prep Problem 1

### About

This repo is for an interview prep group to practice basic coding problems that one would see in a technical interview. This is the first problem in the series.

### Envirionment

For this problem, you are expected to use either Python (version 3.7.x) or Java.

### How to use this repo

To complete this problem you are expected to:

1. Fork this repo to your own github account
2. Pull your forked repo to your local machine
3. Commit any code changes you make
    * It is encouraged to use multiple branches and many commits to get into the practice of doing so
4. Push the changes made to the repo to your forked copy on github
5. Subimt a pull request to this original repo

### Problem

You are to create a command line program, using as many proper programming practices as you know, that takes in a comma sepatated list of unsorted integers, eg: `1, 5, 9, 20, -3, 5` , from a file, sort them, and implement a method to get the occurances of each unique value. 

If a search value is not specified, the user should be prompted to provide one, but also given the option to display a list of all unique values and the number of occurances.

The user should be able to specify that all of the values and their occurances should be outputed as well.

The user should be able to specify an output file to write the sorted list, and a list of all of the unique values and their occurances.

How you implement this is up to you.

Your command line arguments should be as follows:
Base command:  
    `'programname' inputfile.txt(required)`  
Optional command arguments:  
    `-s searchValue` (optional) 
    `-all` (optional)  
    `-o outputlist.txt` (optional)  
    `-v outputvalues.txt` (optional)  

Make sure to write documentation for your specific implementation.

You should aim to finish this within an hour.  
Good luck!