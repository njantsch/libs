# libs

![C Language](https://img.shields.io/badge/language-C-blue.svg)

A custom C library that includes re-implemented standard libc functions and additional unique functions for various string and list manipulation tasks.

## Introduction

In this project, I have recoded several essentail libc functions based on their definitions in the man pages. Additionally, I've introduced a set of unique functions to enhance string manipulation and linked list handling.

## Reimplemented Standard Functions

I have recreated the following standard libc functions:

- `printf`
- `memset`
- `bzero`
- `memcpy`
- `memmove`
- `memcmp`
- `strlen`
- `strdup`
- `strlcpy`
- `isalpha`
- `isdigit`
- `isalnum`
- `isascii`
- `isprint`
- `strlcat`
- `toupper`
- `tolower`
- `strchr`
- `strrchr`
- `strncmp`
- `memchr`
- `strnstr`
- `atoi`
- `calloc`

## Unique Functions

In addition to the standard functions, I've implemented the following unique functions:

- `get_next_line`: A function that returns a line read from a file descriptor
- `ft_substr`: Allocates and returns a substring of a given string.
- `ft_strjoin`: Concatenates two strings and returns a new one.
- `ft_strtrim`: Creates a new string with specified characters removed from the beginning and end.
- `ft_split`: Splits a string into an array of substrings using a delimiter.
- `ft_itoa`: Converts an integer to a string.
- `ft_strmapi`: Applies a function to each character of a string to create a new string.
- `ft_striteri`: Applies a function to each character of a string with its index.
- `ft_putchar_fd`: Outputs a string to a file descriptor.
- `ft_putendl_fd`: Outputs a string followed by a newline to a file descriptor.
- `ft_putnbr_fd`: Outputs an integer to a file descriptor.
- `ft_lstnew`: Creates a new linked list element.
- `ft_lstadd_front`: Adds an element to the beginning of a linked list.
- `ft_lstsize`: Counts the number of elements in a linked list.
- `ft_lstlast`: Gets the last element of a linked list.
- `ft_lstadd_back`: Adds an element to the end of a linked list.
- `ft_lstdelone`: Deletes an element from a linked list and frees its memory.
- `ft_lstclear`: Deletes all elements of a linked list and frees their memory.
- `ft_lstiter`: Iterates through a linked list and applies a function to each element.
- `ft_lstmap`: Iterates through a linked list, applies a function, and creates a new linked list.
