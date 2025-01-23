# Libft

Libft is the first project at School 42, designed to introduce students to the basics of C programming and library creation. The goal is to implement a custom library of functions that mimic standard C library functions, with additional features for future projects.

## Project Details
- **Score**: 125/100
- **Language**: C

This repository contains all mandatory and bonus functions as specified in the project requirements.

## Features
### Mandatory Part
- Reimplementation of standard C library functions, such as:
  - String manipulation: `ft_strlen`, `ft_strcpy`, `ft_strdup`
  - Memory handling: `ft_memset`, `ft_bzero`, `ft_memcpy`
  - Character checks: `ft_isalpha`, `ft_isdigit`, `ft_tolower`
- Other utility functions for common tasks.

### Bonus Part
- Linked list management functions: `ft_lstnew`, `ft_lstadd_front`, `ft_lstdelone`, etc.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd libft42
   ```

## Compilation
To compile the library, use the included `Makefile`:
```bash
make
```

This will generate the `libft.a` static library file.

## Usage
Include the library in your C projects:
```c
#include "libft.h"
```


## Advice for Success
- **Understand the Basics**: Master the functionality of each function before implementing it.
- **Testing**: Write test cases for each function to validate correctness and handle edge cases.
- **Memory Management**: Be cautious about memory allocation and deallocation.
- **Modularity**: Keep your code organized and modular for easier debugging and readability.
- **Learn the Makefile**: Understanding how a `Makefile` works will help you manage your projects more efficiently.

## Good Luck!
Libft is the foundation of many future projects at 42. Take your time to understand each function deeply, and don’t hesitate to ask for help or refer to online resources. Best of luck on your journey!
