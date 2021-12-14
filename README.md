# BrainFuck
 Brainfuck is an esoteric programming language created in 1993 by Urban Müller.
 BrainFuck is executed on a memory array. By default, it's a 30k-cell-long array of 8-bit integers, but some other implementations are more flexible.  
 There are two registers : Instruction pointer and Memory Pointer.  
 Finally, there are 8 instructions:
 
 
 
 ">" : Move memory pointer to the right and go to next instruction 
 
 "<" : Move memory pointer to the left and go to next instruction 
 
 "+" : Increment memory cell and go to next instruction 
 
 "-" : Decrement memory cell and go to next instruction 
 
 "," : Read char from input and store in memory then go to next instruction 
 
 "." : Write memory value as ASCII char to output then go to next instruction
 
 "[" : Go to next instruction if cell is not null, or to the matching closing "]" if null
 
 "]" : Go back to the matching opening "[" if cell is not null, or go to next instruction if null
 
 Go here to try the BF yourself: http://www.bf.doleczek.pl/

