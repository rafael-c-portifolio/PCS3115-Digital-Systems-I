Basic Stack Processor in VHDL - PCS3115 Digital Systems I

This project was completed as part of the PCS3115 - Digital Systems I course. The main objective was to design and implement the VHDL code for all key components of a basic stack processor. This included developing the Arithmetic Logic Unit (ALU), Random Access Memory (RAM), Read-Only Memory (ROM), assembly instructions, data flow, and the register banks.

Project Overview

The project focused on designing a basic stack processor using VHDL (VHSIC Hardware Description Language). The design encompassed all core components of a stack processor architecture, with the aim of understanding and applying digital systems design principles.

Components Implemented:
ALU (Arithmetic Logic Unit): Responsible for executing arithmetic and logic operations.
RAM (Random Access Memory): Used to store temporary data and intermediate results.
ROM (Read-Only Memory): Held the processor's instructions.
Assembly Instructions: Developed custom assembly language instructions for the processor.
Data Flow and Control Unit: Managed the data flow between components and directed the processor's operations.
Register Banks: Included a stack-based register system for handling data during execution.

Design Process

1. ALU Design
The ALU was designed to perform basic arithmetic and logical operations, such as addition, subtraction, AND, OR, and XOR. The VHDL code was written to handle different operation codes (opcodes) that were fed from the ROM and controlled by the processor's instruction set.
2. RAM and ROM Design
RAM: A block of RAM was designed using VHDL to store temporary data and variables during processor operation. The stack-based approach was used to implement a Last-In-First-Out (LIFO) data management structure.
ROM: The ROM component was created to store the processor's instructions. These instructions were fetched and decoded by the control unit to direct the operations of the ALU and other components.
3. Assembly Language Instructions
Custom assembly instructions were developed for the processor. These included basic operations like load, store, push, pop, add, subtract, and conditional jumps. The VHDL implementation ensured that these instructions could be executed in the correct order.
4. Data Flow and Control
The data flow within the processor was carefully designed to ensure efficient communication between components. The control unit managed the instruction fetch, decode, and execution cycle, ensuring the ALU, RAM, ROM, and registers interacted correctly.
5. Register Banks
A stack-based register bank was implemented to handle data storage during processing. The push and pop operations allowed for data to be easily manipulated on the stack, in line with stack processor architecture principles.

Tools and Methodology

VHDL: All components were designed and implemented in VHDL, a hardware description language used for designing and simulating digital systems.
Simulation Tools: We used ModelSim to simulate the processor components and verify the correct operation of the ALU, RAM, ROM, and data flow.
FPGA Implementation (Optional): While not mandatory for this project, the VHDL code could be synthesized onto an FPGA to create a working physical model of the processor.
Challenges and Learning Outcomes
Complexity of Data Flow: One of the biggest challenges was managing the flow of data between the ALU, memory units, and the control unit. Ensuring the correct timing and synchronization of operations required careful planning and testing.

Instruction Set Design: Designing a custom assembly language required a deep understanding of how instructions interact with processor components. The challenge was to create a simple but functional set of instructions that covered all necessary operations.

VHDL Proficiency: Writing VHDL code for each component provided extensive hands-on experience with hardware description languages. Debugging and simulating the code also reinforced the importance of testing in hardware design.

Conclusion
The Basic Stack Processor project for PCS3115 provided a valuable opportunity to understand the inner workings of processor architecture, including how different components interact and how instructions are executed. By designing the processor in VHDL, we gained hands-on experience in digital systems design, from the ALU to memory units, data flow control, and custom instruction set creation.
