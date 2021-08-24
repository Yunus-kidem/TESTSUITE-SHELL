# TESTSUITE-SHELL
## Test Suite | Simple Shell Project | ALX

### ABOUT THE SIMPLE SHELL PROJECT
The repository is a [ALX project](https://www.alxafrica.com/software/) Project. The project consisted in writing a shell like sh (Bourne Shell) by Stephen Bourne  , in **C**, using a limited number of standard library functions, So Instead we used our own function that we rewrited over the past three month [Here](https://github.com/Yunus-kidem/alx-low_level_programming)

The goal in this project was to make us understand how a shell works.

## Usage
In order to run this program,
Clone The simple shell Repo 

`` https://github.com/Yunus-kidem/simpleShell ``

compile it with

`gcc 4.8.4 -Wall -Werror -Wextra -pedantic *.c -o hsh`.
You can then run it by invoking `./hsh` in that same directory.

### How to use it
In order to use this shell, in a terminal, first run the program:
`prompt$ ./hsh`
It will then display a simple prompt and wait for commands.  
`$ `   
A command will be of the type `$ command`  
This shell can handle two types of commands: builtins and normal program.
##### List of built-ins
Displays the environment variable
* exit [exitstatus]  
Exit from the program with exitstatus value. 
* getenv NAME 
  
* cd [directory]  
Switch to the specified directory (path).
* env   
Return the value of the NAME variable if it is in the environment
* help [command]  
Displays the syntax for the command, or all commands.  
* history  
Displays the last typed user .
* echo [$$] or [$?] or [$PATH]
Return pid and exit statue and PATH.
##### Command
Basically Every Program in `$PATH`
It Support Single Word like `ls` 

It Handle Path `ls /tmp`

it Handle Options Like `ls -l`

it Handle All Three Togther Like `ls -l /var `

it Handle Command Path Also Like `/bin/ls` And All The Option And Path Like `/bin/ls -l /var`

it Handle Comments **#** 

## Authors of that simple shell project 
* Yunus Kidem [Yunus-Kidem](https://github.com/Yunus-kidem)
* Obed Amoako [Obed Amoako ](https://github.com/Obed101)

<p align="center">
  <img src="https://lh3.googleusercontent.com/dGNCpJSFY19ck4PkKuIL3ckLjPElmmvUQJSRVNcblB91ua2Oe1_bNhKL3TznvHhitRNB2Q7xoHj2ufbjL1STlIL8XfeGIde4fw=s0" alt="ALX School logo">
</p>
