# get_next_line
>Program that will read a file descriptor(fd) line by line. 

</p>
<p align="center">
	<a href="#about">About</a> •
	<a href="#usage">Usage</a> •
	<a href="#norme">Norme</a>
</p>

## About
The get_next_line project consists of creating a function that reads a file descriptor line by line and returns the next line each time it's called. The bonus part of this project requires altering the function so that it can handle multiple file descriptors simultaneously. This project aims to reinforce concepts such as memory management, file descriptors, and string manipulation. 

## Usage
#### 1st - Clone the repository

#### 2nd - Enter the project folder and compile
``` bash
cd get_next_line/src

[Flags] -Wall -Wextra -Werror
[Mandatory] cc [Flags] main.c get_next_line.c get_next_line_utils.c
[Bonus] cc [Flags] main.c get_next_line_bonus.c get_next_line_utils_bonus.c
```

The main.c function is not included in this repository.

#### 3rd - Execution with one or multiple file descriptors/standard input
``` c
./a.out [text.txt]
./a.out [text1.txt] [text2.txt]
```
## Norme

All 42 projects must be written following the **Norme**.

	- No for, do while, switch, case or goto are allowed
	- No more than 25 lines per function and 5 functions per file
	- No assigns and declarations in the same line (unless static)
 	- Each line must be at most 80 columns wide, comments included
	- A function can take 4 named parameters maximum
	- No more than 5 variables in 1 function
