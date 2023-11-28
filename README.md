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

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
Halfadder:
![exp3hacode](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/acd6e3a6-237b-479a-88eb-7c84f7fce14c)

Fulladder:
![exp3facode](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/a7e3c49a-cc60-45b5-bfcb-bb66d4986b1f)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Visalan H
RegisterNumber: 23007458
*/
 ## TRUTHTABLE
 Halfadder:
![exp3hatt](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/949b9355-3563-4669-a515-3ef6c3ab5aaa)

Fulladder:
![exp3fatt](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/574cd9cd-c5b6-489d-9565-2c834f4c25cb)

RTL realization
Halfadder:
![exp3hartl](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/630bd7e2-564e-4a6b-96b0-515080b20e2d)

Fulladder:
![exp3fartl](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/7ac6da66-edc8-48e7-b331-ab7e6c5636f2)


### Output:
Halfadder:
![exp3haoutput](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/3e4a13db-4370-4275-af87-5d9e3d514cdd)

Fulladder:
![exp3faoutput](https://github.com/Visalan-H/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152077751/db4abfc3-fea4-4b1f-97a4-9feec4196de4)

### RTL
### TIMING DIAGRAM


### TRUTH TABLE 

### Result:
