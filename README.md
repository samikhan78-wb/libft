# libft

**libft** is a custom C library that reimplements a set of standard C library functions, along with additional utility functions.  
This project is designed to help understand how common C functions work internally and to build a reusable library for future projects.

---

## 📚 Project Overview

The goal of **libft** is to create your own static library (`libft.a`) by re-coding a selection of functions from the standard C library, as well as some additional helper functions.

Once completed, this library can be linked to other C projects.

---

## 🛠️ Features

The library is divided into several parts:

### Part 1 – Libc Functions
Reimplementation of standard C library functions such as:
- `ft_strlen`
- `ft_strcpy`
- `ft_strncmp`
- `ft_strdup`
- `ft_memset`
- `ft_memcpy`
- `ft_memmove`
- `ft_bzero`
- `ft_atoi`
- `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- `ft_tolower`, `ft_toupper`

### Part 2 – Additional Functions
Utility functions not present in libc, for example:
- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

---

## ⚙️ Compilation

To compile the library, run:

```bash
make
