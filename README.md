# **_printf**

## Introduction

```_printf``` is a team project which is part of the requirments to be certified as Software Engineer under the [ALX Software Engineering specialization](https://www.alxafrica.com/software-engineering-2022/). The aim of the project is the do a custom implementation of ```printf```. **Printf** is a standard library function in the C programming language that prints ```Arguements``` according to a ```format``` or execures accoding to a specified option.

## Prototype

Prototype: ```int _printf(const char *format, ...);```

## Examples
### Print a String
* Input: ```_printf("%s\n", "First ALX Team Project");```
* Output: ```First ALX Team Project```

### Print a Character
* Input: ```_printf("%c for Apple\n", 'A');```
* Output: ```A for Apple```

### Print an Integer
* Input: ```_printf("Today is the %ith day of the October\n", 19);```
* Output: ```Today is the 19th day of the October```

### Print a Float
* Input/Code: ```_printf("pi = %.3f\n", 22.0 / 7);```
* Output: ```pi = 3.142857```

## Project Requirements
* All files be compiled on Ubuntu 20.04 LTS using ```gcc```, using the options ```-Wall -Werror -Wextra -pedantic -std=gnu89```
* All codes to adhere to the [Betty Coding style](https://github.com/holbertonschool/Betty)
* _printf should return the number of characters printed (excluding the null byte used to end output to strings)
* _printf should write output to stdout, the standard output stream according to the specified format

## Project Tasks

- [x] **Task 0**
* Write a function that produces output according to a ```format```. You need to handle the following conversion specifiers:
	* c
	* s
	* %
* You don’t have to reproduce the buffer handling of the C library printf function
* You don’t have to handle the flag characters
* You don’t have to handle field width
* You don’t have to handle precision
* You don’t have to handle the length modifiers

- [x] **Task 1**
* Write a function that produces output according to a ```format```. Handle the following conversion specifiers:
	* d
	* i
* You don’t have to handle the flag characters
* You don’t have to handle field width
* You don’t have to handle precision
* You don’t have to handle the length modifiers
* creat man page for printf
