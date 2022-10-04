# Bash

 **B**ourne-**A**gain **SH**ell

### What is a Script?

A shell script is a file containing commands for the shell.

A Bash script is simply a file containing commands for the Bash shell.

### Why use scirpts?

Scripts Allow Automation

### What is shell?

The shell is **command-line interpreter** that makes it easy for you to issue commands to your operating system


### Files permissions

["Permissions Calculator"](https://chmod-calculator.com/)

1234567890

1 -> - or d -> - = file and d = directory

#### file owner
2 -> - or r -> read permission -> - or r -> i - no and r - yes  
3 -> - or w -> write permission -> - or w -> i - no and w - yes  
4 -> - or x -> execute permission -> - or x -> i - no and x - yes  

#### files group
5 -> - or r -> read permission -> - or r -> i - no and r - yes  
6 -> - or w -> write permission -> - or w -> i - no and w - yes  
7 -> - or x -> execute permission -> - or x -> i - no and x - yes  

#### other users
8 -> - or r -> read permission -> - or r -> i - no and r - yes  
9 -> - or w -> write permission -> - or w -> i - no and w - yes  
0 -> - or x -> execute permission -> - or x -> i - no and x - yes  

### PATH

The PATH variable tells the shell where to search for **executable** files

We can add folders to our PATH variable by modifying the **.profile** file

Try to avoid giving your scripts names that may conflict with another command on the system

Sample:

```sh
export PATH="$PATH:$HOME/github/bash_course/scripts"
```

### Types of shell parameters:

- Variables
- Positional parameters
- Special parameters


### Shell variables

- Bourne Shell Variables
  - Bourne shell (created by Stephen Bourne 1979)
  - 10 in total

- Bash Shell Variables
  - Bash shell (based on the bourne shell)
  - Bourne Again SHell (BASH)
  - Around 95 in total


