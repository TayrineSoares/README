# Tayrine's notes 
## Sumary 
This repository contains the notes taken by [Tayrine](https://github.com/TayrineSoares) for the [Lighthouse Labs](https://www.lighthouselabs.ca/) Web Development Bootcamp.


## Table of Contents
- [Week 1](/Week-1)

  [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

  - [Day 1](/Week-1/Day_1/)

    #### Command Line Args 
    Command line arguments can be used to make a program more flexible and adaptable to different situations without needing to modify the code.
    
    Consider a more complex example, such as a program that manipulates files. You could use command line arguments to specify which file to manipulate and what operation to perform. This would allow the user to use your program in a variety of situations without needing to change the code.

    Using command line arguments can significantly enhance a program by making it more flexible and capable of handling different user inputs without changing the script's code. For example, if you have a program that backs up files, you can use command line arguments to specify which files to back up and where to save the backup. Here’s a hypothetical command line usage:

     ``` node backup.js /path/to/source /path/to/destination ```

     In the script, you could access these paths with ```process.argv[2]``` and ```process.argv[3]```, allowing the user to dynamically specify the source and destination directories each time the script is run.