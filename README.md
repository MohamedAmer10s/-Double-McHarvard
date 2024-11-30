This project implements a Harvard Architecture processor with separate instruction and data memories. The instruction memory is 1024 × 16 bits, and the data memory is 2048 × 8 bits, ensuring efficient data and program handling. The processor features 66 registers, including 64 general-purpose registers, a status register (SREG) with key flags, and a 16-bit program counter.

The processor supports a 16-bit instruction set with 12 operations, divided into R-Format and I-Format. These include arithmetic, logic, memory, and control instructions. A 3-stage pipeline (Instruction Fetch, Decode, and Execute) allows parallel execution of up to three instructions, optimizing performance.

This architecture is suitable for applications requiring efficient computation and streamlined memory access, ideal for embedded systems or learning environments focused on processor design and assembly programming.
