Open Source Software Capstone Project

***Software chosen by me is Git

BY
DESHAIPETA CHANDRA SHEKHAR(24MIM10066)

1. Introduction

This project is developed as part of the Open Source Software course. The motive of this project is to understand the working of Linux-based open-source systems and to gain practical experience in shell scripting.

Linux gives a command-line interface where we can perform tasks using commands and scripts that allow automation of repetitive tasks. in this project, five different shell scripts have been created to demonstrate various concepts such as system information retrieval, package management, directory analysis, file processing, and user interaction.


2. Objectives

a.to understand the concept of open-source software  
b.to learn basic Linux commands and shell scripting  
c.to automate system-level tasks using Bash scripting  
d.to analyze files and directories using Linux utilities  
e.to implement user interaction in shell scripts  


3. Tools and Environment

a.Operating System:Ubuntu Linux (WSL)  
b.Shell:Bash  
c.Editor:Nano  
d.Version Control:Git  


4. Description of Scripts

 4.1 Script-1:System Information Script

This script displays basic system and user information such as:
a.Username  
b.Home directory  
c.Current date and time  
d.System uptime  

Purpose:  
To understand how to retrieve system-level information using Linux commands.


4.2 Script-2: FOSS Package Inspector

This script checks whether a specific package (e.g., git) is installed or not. It also:
a.Displays package details using `dpkg`  
b.Shows version information  
c.Provides a short description using a case statement  

Purpose:  
To learn package management and conditional statements in shell scripting.


 4.3 Script-3: Directory Audit Script

This script analyzes important system directories such as:
a. `/etc`  
b. `/var/log`  
c. `/home`  
d. `/usr/bin`  
e. `/tmp`  

It displays:
a. Permissions  
b. Owner information  
c. Directory size  

Purpose:  
To understand file permissions, directory structures, and system auditing.


4.4 Script-4: Log/File Analyzer

This script takes:
a.A filename as input  
b.A keyword (optional, default = "error")  

It performs:
a.File existence check  
b.Empty file check  
c.Counts occurrences of the keyword  
d.Displays last 5 matching lines  

Purpose:  
To learn file handling, loops, and text processing using tools like `grep`.


4.5 Script-5: Open Source Manifesto Generator

This script interacts with the user by asking three questions:
a. Name of an open-source tool used daily  
b. Meaning of freedom (in one word)  
c. Something the user would build and share freely  

It then:
a. Generates a manifesto  
b. Saves it into a file (`manifesto_avinash.txt`)  
c. Displays the output  

Purpose: 
To understand user input, string handling, and file creation in shell scripting.




5. How to Execute the Scripts

Step-1: Give execution permission
bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

Step-2: Run scripts
./script1.sh
./script2.sh
./script3.sh
./script4.sh <filename> <keyword>
./script5.sh


6. Output

Each script generates appropriate output based on its functionality:

Script-1: Displays system information
Script-2: Shows package details and version
Script-3: Displays directory permissions and sizes
Script-4: Shows keyword count and matching lines
Script-5: Generates and saves a manifesto file

7. Learning Outcomes

Through this project, the following concepts were learned:
  Basics of shell scripting
  Use of Linux commands (ls, grep, dpkg, df, free)
  Conditional statements (if-else)
  Looping (while)
  Case statements
  File handling and text processing
  User interaction in scripts


8. Conclusion

This project provides a practical understanding of Linux shell scripting and open-source tools. It demonstrates how automation can simplify system tasks and how open-source software promotes collaboration, transparency, and innovation.

9. Repository Contents
script1.sh
script2.sh
script3.sh
script4.sh
script5.sh
README.md
