# Password-Generator

This project is a beginner-friendly Python application that generates secure passwords based on user input. 
It includes two separate versions—Sequenced and Unsequenced—to demonstrate both basic and slightly more 
advanced concepts of password generation using randomness and list manipulation.

The Sequenced Version is the simpler approach. In this version, the generated password is constructed in a 
fixed order: first the letters, followed by the symbols, and finally the numbers. For example, if a user 
chooses 4 letters, 2 symbols, and 3 numbers, the result might be something like Abcd$*924. This version is 
great for learning how to use Python lists, loops, and random.choice() for deterministic generation.

The Unsequenced Version takes it one step further by randomizing the order of all characters in the final 
password. After collecting the desired number of letters, symbols, and numbers, the characters are shuffled 
using random.shuffle(), resulting in a much stronger and less predictable password. An example output might 
be x$d24g*f9, where letters, numbers, and symbols are randomly distributed.

Both scripts prompt the user for their desired password length and character type distribution, making them 
interactive and customizable. These small scripts are an excellent introduction to Python fundamentals like 
user input, loops, and the random module.
