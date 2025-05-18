# ARITHMETIC-LOGIC-UNIT-ALU-

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: KORADA BHASKARA RAO

*INTER ID*: CT06DL1260

*DOMAIN*: VLSI

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

Design and Simulation of a Basic ALU Using Verilog in Xilinx VivadoThe objective of this project was to design a basic Arithmetic Logic Unit (ALU) using Verilog HDL and simulate it using the Xilinx Vivado Design Suite. An ALU is a critical component in the architecture of a microprocessor or CPU, responsible for performing both arithmetic and logical operations. This project focused on building a simplified version of an ALU that supports five operations: Addition, Subtraction, AND, OR, and NOT.The objective of this project was to design a basic Arithmetic Logic Unit (ALU) using Verilog HDL and simulate it using the Xilinx Vivado Design Suite. An ALU is a critical component in the architecture of a microprocessor or CPU, responsible for performing both arithmetic and logical operations. This project focused on building a simplified version of an ALU that supports five operations: Addition, Subtraction, AND, OR, and NOT.
Design Process:
The design was implemented using Verilog, a hardware description language (HDL) widely used for designing digital logic circuits. The ALU module takes two 4-bit inputs (A and B), a 3-bit selector input (sel), and produces a 4-bit output (result). The selector input determines the operation to be executed. The operations are defined as follows:

sel = 000: Perform Addition (A + B)

sel = 001: Perform Subtraction (A - B)

sel = 010: Perform Bitwise AND (A & B)

sel = 011: Perform Bitwise OR (A | B)

sel = 100: Perform Bitwise NOT on A (~A)

A case statement within an always block was used to evaluate the operation based on the selection input. This modular design allows for easy extension of additional operations in the future.Testbench Development:A testbench was written in Verilog to verify the functionality of the ALU. The testbench creates instances of the inputs and cycles through all the operations by changing the sel signal while holding the input values constant. This setup ensures that each operation is tested with predictable input values, and the outputs are displayed using the $display system task in the simulation.Tool Used – Vivado:The entire development and simulation were carried out in the Xilinx Vivado Design Suite, a powerful tool for RTL design, simulation, synthesis, and FPGA implementation. The steps followed in Vivado included:Creating a new project with Verilog as the target language.Adding Verilog source files for the ALU and the testbench.Running behavioral simulation to verify the logical correctness of the ALU.Observing waveform results and console outputs to confirm expected behavior.Vivado’s simulation tools provided a clear interface for debugging and verifying the design. Waveform analysis ensured that the result matched the operation selected through the control signals.Conclusion:This project successfully demonstrated the design and simulation of a basic ALU using Verilog in Vivado. All five operations were correctly implemented and tested using a functional testbench. The project helped solidify an understanding of digital logic design, Verilog syntax, simulation techniques, and usage of the Vivado toolchain. This forms a fundamental building block in learning processor design and digital system development.
