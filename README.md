# Brainfuck

In this project, we are going to program in Brainfuck. Brainfuck is an esoteric programming language known for its simplicity and extreme minimalism.

## Instructions

1. Start with a pointer at the current cell, initialized to 0.
2. Read the Brainfuck code, which consists of a series of special characters.
3. Perform the following operations based on the encountered characters:

    - `>`: Move the pointer to the next cell.
    - `<`: Move the pointer to the previous cell.
    - `+`: Increment the value of the current cell by 1.
    - `-`: Decrement the value of the current cell by 1.
    - `.`: Print the ASCII value of the current cell.
    - `,`: Read an ASCII value from the input and store it in the current cell.
    - `[`: If the value of the current cell is 0, jump to the instruction after the corresponding closing bracket.
    - `]`: If the value of the current cell is not 0, jump to the instruction after the corresponding opening bracket.

4. Repeat step 3 until all the Brainfuck code has been executed.
