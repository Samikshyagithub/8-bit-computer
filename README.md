We have incorporated 16 distinct instructions tailored to the specific requirements of 
our project. Our computer, named "RS8," employs a 4-bit opcode and a 4-bit address 
length. The hardware components of our computer include:
1. A memory with a capacity of 16x8.
2. Eight registers: IR, PC, A, B, OR, MBR, MAR, and SC.
3. A Binary to 7 Segment converter.
4. An 8-bit internal Bus.
5. Both 4-bit and 8-bit External Buses.
6. A Control Unit designed using Logisim's combinational analysis.
7. An Arithmetic Logic Unit (ALU) supporting operations such as addition, 
subtraction, XOR, AND, OR, etc

INSTRUCTION FORMAT
There are two parts of an instruction that can be divided into. They are:
Operation Code (Opcode): It specifies the operation for an instruction.
Address: It specifies the registers and/or memory locations assigned for a specific 
operation. In the case of an 8-bit computer, its inherent design dictates a word size of 
8 bits. The Memory Address Register (MAR), responsible for storing RAM addresses, 
is designed with a 4-bit capacity. Consequently, the RAM size is limited to 2^4 = 16 
bytes.

ADDRESSING MODES
Immediate Addressing
The address of the operand is loaded directly into the A register in immediate 
addressing mode.
Direct Addressing
The address of the operand is stored in the memory location specified in the
instruction in the direct addressing mode.

