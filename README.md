### NAME: FRANKLIN.F
### REF NO.:24900641
# EXPERIMENT 4: IMPLEMENTATION OF FULL ADDER SUBTRACTOR

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# Figure -1 FULL ADDER

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# Truthtable
![WhatsApp Image 2024-11-28 at 14 35 13_a46d0032](https://github.com/user-attachments/assets/e26138ae-0291-40c3-9a35-ab410a44ad62)

# Procedure
Implementing FULL ADDER AND SUBTRACTOR in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.

# Program:
![Screenshot (8)](https://github.com/user-attachments/assets/a54f23c6-e654-4e5d-8da4-5bedf5655044)


# RTL Schematic
![Screenshot (11)](https://github.com/user-attachments/assets/3d0fa6f8-ff42-4c30-85de-ecfa7befa801)

# Output Timing Waveform
![Screenshot (10)](https://github.com/user-attachments/assets/f6fc5cb6-38df-402b-8cf7-db06ccfe4460)

# Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



