# verilog_basics
Verilog basics for quick review

## Unit 4:
### 1. Continuous assignment:
left-hand parameters are net (either wire or tri)
executes whenever the right side parameters change
used for combinational circuit/block

### 2. Procedural assignment:
initial or always blocks, a typical processor can have multiple always blocks. always blocks run in parallel. nested blocks are not allowed. statements inside a processor execute sequentially.

left-hand side parameter should be variable, integer, or real.
**Blocking assignment**: a = b; blocks the next statement until it finish, updated a is ready to use
**Blocking assignment**: a <= b; does not block the next statement, updates a value at the end of the block. 

![image](https://github.com/RajuMachupalli/verilog_basics/assets/52839597/1bd9e4b0-19f1-4d2e-88f6-9bd5af0ef680)

assigning parameters from high level to low level modules
![image](https://github.com/RajuMachupalli/verilog_basics/assets/52839597/afa0f9ee-4139-4ec7-94e6-c995bd1f7db4)



