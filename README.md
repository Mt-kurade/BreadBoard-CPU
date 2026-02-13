# BreadBoard-CPU


## 4-bit ALU 
To build the the 4-bit ALU, its imporant to understand the working of a 1 bit ALU

### 1-bit ALU 
There are 4 main inputs, 4 gates and a multiplexer that are important. 

The first two inputs are the user number inputs (X, Y), these are the numbers that will have the operations conducted apon 
The last two inputs are also input by the user but processed by the computer to be the operand that will be executed on the input bits X and Y. These are called the S0 and S1 inputs. These decide the mathematical operations (AND, OR, XOR, NOT). 

The 4 gates (AND, OR, XOR, NOT) do the calculations for the two input bits (X, Y). The gates compute all the possible results. 

The Multiplexer (or MUX) simply selects which of the results from the calculations outside the MUX will be output to the user based on the S1 and S2 input for mathematical operation. This selected value by the MUX will become the output (Y). 

The gates outside the multiplexer perform different logical operatiosn on A and B simultaneously. Their outputs are connected to the MUX, which selects one results accoridng to the control inputs (S0 and S1)
