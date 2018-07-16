# C for Geeks

<p align="center">
  <img alt="Banner" src="images/banner.png">
</p>

## Prerequisites

Windows users should set up WSL.

- basic commandline fu (navigation, file / folder manipulation, ...)
- your favourite text editor
- GCC / Clang installed

## Syllabus

See [my C programming repo](https://github.com/W4RH4WK/UIBK-703004-C-Programming) for code examples.

- **Lecture -2:** mathematics background
    - numbers and their representation (base 2, 8, 10, 16)
    - bits and bytes, and their limitations
    - ASCII
    - boolean logic
    - bitwise operations
    - set theory
    - functions
    - types

- **Lecture -1:** computer architecture
    - CPU / memory
    - op-codes
    - locality

- **Lecture 0:** empty program
    - syntax
    - `void`
    - compiler warnings / errors

- **Lecture 1:** Hello World
    - use of standard library
    - man-pages

- **Lecture 2:** variables
    - types
    - assignment
    - `sizeof`
    - different ways to write a number
    - boolean in C
    - scope

- **Lecture 3:** Simple I/O
    - `puts` / `printf`
    - `getchar` / `scanf`

- **Lecture 4:** arithmetic
    - precedence
    - integer arithmetic
    - floating point arithmetic
    - bitwise operations
    - boolean operations
        - short circuit evaluation
    - comparison operations
    - compound assignment
    - increment / decrement operators
        - sequence points

- **Lecture 5:** Branching
    - `if` / `else`
    - `switch`

- **Lecture 6:** Loops
    - `while` / `do while`
    - `for`
    - `break` / `continue`
    - `goto`

- **Exercise:** [Fizz-Buzz](https://en.wikipedia.org/wiki/Fizz_buzz)
    - Output all numbers from 1 to 100 (one per line).
    - Any number divisible by 3 is replaced by *fizz*.
    - Any number divisible by 5 is replaced by *buzz*.
    - Any number divisible by 3 and 5 is replaced by *fizzbuzz*.

- **Exercise:** *Zapfen*
    - Read in integer from user.
    - Continuously multiply with numbers from 2 to 12 (inclusive).
    - Then continuously divide by numbers from 12 to 2 (inclusive).
    - Try this for large user inputs.
    - Try this with unsigned.
    - Try this with float.

- **Exercise:** [Mastermind](https://en.wikipedia.org/wiki/Mastermind_(board_game))
    - See `rand(3)`.
    - Randomly pick 4 integers between 1 and 6 (inclusive).
    - User has to guess the combination by entering the sequence of numbers separated by spaces.
    - User can guess 10 times.
    - Game ends when user guessed correctly or all guesses have been exceeded.
    - Program will output hints on wrong guesses.

- **Exercise:** [Pascal's triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle)
    - Calculate the first 10 rows of Pascal's triangle and print them.

- **Lecture 7:** Functions
    - normal
    - recursion

- **Lecture 8:** Pointers

- **Lecture 9:** Arrays
    - 1D
    - more dimensions
    - strings
    - pointer-decay

- **Lecture 10:** Enums

- **Lecture 11:** `struct`
    - `union`
    - recursive structures

- **Exercise:** [Levenshtein distance](https://en.wikipedia.org/wiki/Levenshtein_distance)
    - Read in two strings from the user.
    - Output the corresponding Levenshtein distance.

- **Exercise:** [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
    - See `fopen(3)` and `fwrite(3)`
    - See [PBM file format](https://en.wikipedia.org/wiki/Netpbm_format#PBM_example).
    - Use hard-coded field size and simulation step count.
    - Initialise the field with random population.
    - Simulate and store each *frame* as file (eg `frame_072.pbm`).
    - Use `convert(1)` (part of [Imagemagick](https://packages.debian.org/stable/imagemagick)) to create an animated GIF.
        - Do not invoke `convert` from your program, use a Bash script.

- **Exercise:** [Mandelbrot](https://en.wikipedia.org/wiki/Mandelbrot_set)
    - Implement a typical visualisation of the Mandelbrot set.
    - You can either use the PGM format or print it as ASCII art.

...
