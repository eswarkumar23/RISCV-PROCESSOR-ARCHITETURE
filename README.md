

## 1 Overall Goal  
 Develop a processor architecture design based on the RISC-V ISA using Verilog. The design should be thoroughly tested to satisfy all the specification requirements using simulations. The project submission must include the following:

- A report describing the design details of the various stages of the processor architecture, the supported features (including simulation snapshots of the features supported) and the challenges encountered.
- Verilog code for processor design and testbench.

## 2 Specifications  
The required specifications in the processor design are as follows:

- A bare minimum processor architecture must implement a sequential design.
- A pipelined processor architecture implementation with a 5-stage pipeline, which includes support for eliminating pipeline hazards.

Your submission should at least have the first design mentioned above in order to get minimal marks. However, your goal should be to submit a design with pipelined architecture.  

### Important points to notice:  
- Both the above implementations must execute the following all instructions from RISC-V ISA.

## 3 Design Approach  
The design approach should be modular, i.e., each stage has to be coded as a separate module and tested independently in order to help the integration without too many issues.



## 4 Suggestions for Design Verification  
Please adhere to the following verification approaches as much as possible:

- You can individually test each stage/module for its intended functionality with module-specific test inputs.
- You can  write an assembly program for any algorithm (e.g., sorting algorithm) using RISC-V ISA and the corresponding encoded instructions and use the encoded instructions to test this  integrated design.
- If possible, you can also think of an automated testbench that will help you to verify your design efficiently, i.e., automatically verify the state of the processor and memory after execution of each instruction in the program.



