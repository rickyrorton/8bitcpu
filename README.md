## 8 Bit CPU
8 bit CPU implented and simulated by Rishi Sriram, based off of SAP architecture described in the book Digital Computer Electronics by Albert Paul Malvino and Jerald A. Brown. Inspired by Ben Eater's [8-bit CPU built entirely on breadboards](https://eater.net/8bit)

![image](https://github.com/rickyrorton/8bitcpu/assets/74890659/bf8e8a7b-b5bb-4ecf-acdc-99b75b04d94f)

Some features of the CPU:
1) 16x8 RAM
2) 2 registers - Accumulator register and temporary register B
3) CPU flags- carry flag and zero flag.

First four bits are the OPCODE and next four bits are the OPERAND (memory location, value(in case of LDI),etc)

## Instruction Set:

0000- NOP

0001- LDA

0010- ADD

0011- SUB

0100- STA

0101- LDI

0110- JMP

0111- JEC

1000- JEZ

1001- 

1010- 

1011- 

1100- 

1101- 

1110- OUT

1111- HLT

## Microcode instructions:

MI- Memory address register in

RI- RAM in

RO- RAM out

II- Instruction register in

IO- Instruction register out

CO- Program counter out

J - Program counter IN (Jump)

CE- Program counter increment

AI- Accumulator in

AO- Accumulator out

EO- Sum out

SU- Subtract

BI- B register in

OI- Output register in

FI- Flags register in
HLT- Halt
