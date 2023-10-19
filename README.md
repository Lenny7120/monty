0x18. C - Stacks, Queues - LIFO, FIFO
Description

This Holberton School project is a custom ByteCode interpreter, coded in C. Compilation: gcc -Wall -Werror -Wextra -pedantic *.c -o monty Usage: ./monty byte_file.m

The program reads from the file "byte_file.m" that contains one instruction per line. It then calls the right function to modify a stack according to the instruction. It prints custom error messages if the instruction is wrong.
Table of contents
File 	Description
main.c 	entry point of the program
monty.h 	main header file
get_func.c 	function that picks the right function for the instruction
handler_funcs1.c 	handler functions for the instructions
handler_funcs2.c 	handler functions for the instructions
handler_funcs3.c 	handler functions for the instructions
list_funcs1.c 	doubly linked list functions
list_funcs2.c 	doubly linked list functions
strtow.c 	string tokenizing functions
free.c 	memory handling functions
char.c 	handler functions for ascii instructions
bf 	Advanced tasks: Brainf*ck programs
