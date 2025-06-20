# Libft

Libft is a custom implementation of a standard C library, developed as a foundational project at [42 School](https://42.fr/en/homepage/). The goal is to recreate common standard library functions from `<string.h>`, `<stdlib.h>`, and `<ctype.h>` — and to build a strong understanding of low-level programming in C.

## 🧠 Purpose

This project is designed to:
- Reinforce a deep understanding of memory management in C.
- Practice using pointers, static and dynamic memory, and basic data structures.
- Create a reusable library of functions that can be used in future C projects.

## 🚀 Features

Libft includes:

### Part 1 – Libc Functions
Reimplementations of standard C functions:
- Memory functions: `memset`, `memcpy`, `memmove`, `bzero`, `calloc`, `memchr`, `memcmp`
- String functions: `strlen`, `strlcpy`, `strlcat`, `strchr`, `strrchr`, `strncmp`, `strnstr`, `strdup`
- Character checks and conversions: `isalpha`, `isdigit`, `isalnum`, `isascii`, `isprint`, `toupper`, `tolower`
- Conversion: `atoi`

### Part 2 – Additional Functions
Utilities to work with strings and memory:
- `substr`, `strjoin`, `strtrim`, `split`
- `itoa`, `strmapi`, `striteri`
- Memory management: `calloc`, `strdup`

### Bonus – Linked List Library
A simple linked list library with:
- `t_list` structure
- Functions like: `lstnew`, `lstadd_front`, `lstadd_back`, `lstsize`, `lstlast`, `lstdelone`, `lstclear`, `lstiter`, `lstmap`

## 🛠️ Technologies

- Language: **C**
- Compiler: `gcc`
- Norme compliant (42’s coding style rules)

## 📚 Skills Developed

- Low-level memory management
- Implementation of standard algorithms
- Pointer arithmetic and dynamic allocation
- Code modularity and reusability
- Clean code and coding standards

## 📦 How to Use

To compile and use `libft.a` in your project:

```bash
git clone https://github.com/yourusername/libft.git
cd libft
make
