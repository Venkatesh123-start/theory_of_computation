# Example Turing Machine: unary increment (informal)

Alphabet: {1, _} where '_' is the blank symbol. Input is a unary number represented as n copies of '1'.

Goal: Given input of the form 111...1 (n ones), output 111...11 (n+1 ones) and halt.

High-level description:
1. Move right to find the blank symbol at the end of the unary block.
2. Replace the blank with '1'.
3. Halt.

This simple TM demonstrates tape movement and write operations. More complex examples (palindrome checking, addition, simulation of machines) can be added.
