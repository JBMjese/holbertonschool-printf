#custom function _printf

The following is a customized and simplified implementation of the **printf** function in the **C** programming language, which has been named **_printf** This function has been designed to allow printing of formatted output to the standard output of the program. The **_printf** function is capable of handling a variety of format specifiers, such as **%d** to print signed integers, **%s** to print strings, and more.

# Files

 - **functions.c**
 - **main.h**
 - **_printf**
 - **sterlen.c**
 - **arr_cases.c**
 - **search_fs.c**

## functions.c

This file contains a set of functions that implement the specific behavior of different format specifiers used in the **_printf** function.

- char cfunct(char *str, va_list arguments) function to add a character to the parent string.
 - char perfunct(char *str, va_list arguments __attribute__((unused))) Function to add a % to the parent string.
 - char add(char *str, char format) Function to add to the parent string.
 - char sfunct(char *str, va_list arguments) Function to add a string to the parent string.
 - function char dfunct(char *str, va_list arguments) Function to add a base 10 number to the parent string.

## main.h

The **main.h** file contains function declarations, structure definitions, and the inclusion of header files necessary for the operation of the program that implements the **_printf** custom function. I
