# Libft
 
*Your Standard C Library for 42 School Projects*

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Functions](#functions)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)
---

## Introduction

**Libft** is a custom C library created as part of the 42 School curriculum. It serves as a foundation for future projects by reimplementing standard C library functions and adding additional utility functions. This project is designed to deepen your understanding of C programming, memory management, and algorithmic thinking.

---

## Features

- **Standard Functions**: Reimplementations of standard C library functions like `malloc`, `free`, `strlen`, `strcpy`, and more.
- **Additional Functions**: Custom utility functions to handle strings, memory, linked lists, and more.
- **Optimized**: Written with efficiency and readability in mind.
- **Extensible**: Easy to add new functions as needed for future projects.

---

## Installation

To use **Libft** in your project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MKNSTEJA/libft.git

2. Navigate to the libft directory:
    ```bash
    cd libft

3. Compile the library:
    ```bash
    make

4. Include the library in your project:
    ```c
    #include "libft.h"

5. Link the library during compilation:
    ```bash
    gcc -Wall -Wextra -Werror -Ilibft -Llibft -lft your_program.c -o your_program

---

## Usage

Once installed, you can use any of the functions provided by **Libft** in your C programs. For example:
  ```c
  #include "libft.h"

  int main(void)
  {
      char *str = "Hello, 42!";
      char *copy = ft_strdup(str);
  
      ft_putendl_fd(copy, 1);
      free(copy);
      return (0);
  }
  ```

---

## Functions

### Standard Library Functions

- **Conversion & Character Checks:**
  - `ft_atoi` – Convert a string to an integer.
  - `ft_isalnum` – Check for alphanumeric characters.
  - `ft_isalpha` – Check for alphabetic characters.
  - `ft_isascii` – Verify if a character is ASCII.
  - `ft_isdigit` – Check if a character is a digit.
  - `ft_isprint` – Check if a character is printable.
  - `ft_tolower` – Convert a character to lowercase.
  - `ft_toupper` – Convert a character to uppercase.

- **Memory Management:**
  - `ft_bzero` – Fill a block of memory with zeroes.
  - `ft_calloc` – Allocate memory and initialize it to zero.
  - `ft_memchr` – Locate a byte in memory.
  - `ft_memcmp` – Compare two memory areas.
  - `ft_memcpy` – Copy memory area.
  - `ft_memmove` – Safely move memory between overlapping areas.
  - `ft_memset` – Fill memory with a constant byte.

- **String Manipulation:**
  - `ft_strdup` – Duplicate a string.
  - `ft_strlen` – Compute the length of a string.
  - `ft_strchr` – Find the first occurrence of a character in a string.
  - `ft_strrchr` – Find the last occurrence of a character in a string.
  - `ft_strncmp` – Compare two strings up to a specified number of characters.
  - `ft_strnstr` – Locate a substring in a string within a given length.
  - `ft_strlcpy` – Copy a string with size constraints.
  - `ft_strlcat` – Concatenate strings ensuring proper buffer size.
  - `ft_strjoin` – Join two strings into a new string.
  - `ft_strtrim` – Trim unwanted characters from the beginning and end of a string.
  - `ft_split` – Split a string into an array of substrings based on a delimiter.
  - `ft_strmapi` – Create a new string by applying a function to each character.
  - `ft_striteri` – Apply a function to each character of a string (in-place).

- **Number Conversion:**
  - `ft_itoa` – Convert an integer to a string.

- **File Descriptor Output:**
  - `ft_putchar_fd` – Output a character to a file descriptor.
  - `ft_putstr_fd` – Output a string to a file descriptor.
  - `ft_putendl_fd` – Output a string with a newline to a file descriptor.
  - `ft_putnbr_fd` – Output an integer to a file descriptor.

### Linked List Functions

- **Basic Linked List Operations:**
  - `ft_lstnew` – Create a new list element.
  - `ft_lstadd_front` – Add an element at the beginning of the list.
  - `ft_lstadd_back` – Add an element at the end of the list.
  - `ft_lstsize` – Count the number of elements in the list.
  - `ft_lstlast` – Retrieve the last element of the list.
  - `ft_lstdelone` – Delete a single list element.
  - `ft_lstclear` – Delete and free the entire list.
  - `ft_lstiter` – Iterate through the list and apply a function to each element.
  - `ft_lstmap` – Map a function to each element and create a new list from the results.

---

### Contributing

Contributions are welcome! If you'd like to contribute to Libft, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
  ```bash
  git checkout -b feature/your-feature-name
  ```

3. Commit your changes:
  ```bash
  git commit -m "Add your commit message here"
  ```

4. Push your branch
  ```bash
  git push origin feature/your-feature-name
  ```

5. Open a pull request and describe your changes.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **42 School:** For providing the opportunity to work on this project.
- **Community:** Thanks to all the peers and mentors who provided feedback and support.

---

## Author

**MKNSTEJA**

- GitHub: [MKNSTEJA](https://github.com/MKNSTEJA)
- Email: chessmaniacs123@gmail.com

---
