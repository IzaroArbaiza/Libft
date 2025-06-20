# 📚 Libft

Libft is a custom implementation of a standard C library, developed as a foundational project at [42 School](https://42.fr/en/homepage/). The goal is to recreate common standard library functions and additional utilities.

## 🔧 Overview
- Language: **C**
- Norme compliant (42 coding style rules)

### Key Concepts Practiced
- Manual memory management and allocation
- String manipulation and character handling
- Static and dynamic data structures
- Implementation of standard library behavior
- Clean, reusable, and modular C code

<br>

## 📋 Fuction List
### Part 1 – Libc Functions
Reimplementations of standard C functions:
- Memory functions: `memset`, `memcpy`, `memmove`, `bzero`, `calloc`, `memchr`, `memcmp`
- String functions: `strlen`, `strlcpy`, `strlcat`, `strchr`, `strrchr`, `strncmp`, `strnstr`, `strdup`
- Character checks and conversions: `isalpha`, `isdigit`, `isalnum`, `isascii`, `isprint`, `toupper`, `tolower`
- Numeric Conversion: `atoi`

### Part 2 – Additional Functions
Utilities to work with strings and memory:
- String functions: `substr`, `strjoin`, `strtrim`, `split`
- String transformation: `itoa`, `strmapi`, `striteri`
- Memory management: `calloc`, `strdup`

<!--### Bonus – Linked List Library
A simple linked list library with:
- `t_list` structure
- List management functions: `lstnew`, `lstadd_front`, `lstadd_back`, `lstsize`, `lstlast`, `lstdelone`, `lstclear`, `lstiter`, `lstmap`
-->
<br>

## 📦🚀 How to Use
<!--To compile and use `libft.a` in your project:-->
Clone the repository
```bash
git clone https://github.com/IzaroArbaiza/Libft.git Libft
```
Get into the folder and compile it with Makefile
```bash
cd Libft && make
```

### 👉🏼 Usage
```C
#include "libft.h"
```
and then don't forget to compile against the library
```Bash
gcc *your files* libft/libft.a -Ilibft
```
