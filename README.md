# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

![Screenshot 2023-11-26 141707](https://github.com/vamsikrishna272005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147477015/ac4139cb-dc44-44bd-b617-f4eca350a75a)

#### Figure -01 HALF ADDER 


![Screenshot 2023-11-26 142950](https://github.com/vamsikrishna272005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147477015/efc86ac7-dd3a-4902-a9ea-2982ee8164a4)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### TIMING DIAGRAM


### TRUTH TABLE 
![Screenshot 2023-11-26 142029](https://github.com/vamsikrishna272005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147477015/6dc7ebe5-1917-4cb3-b281-f7742975625f)

### Result:
