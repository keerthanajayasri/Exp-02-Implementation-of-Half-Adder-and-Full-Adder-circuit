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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: keerthana jayasri 
RegisterNumber:  212222110019
*/


![Screenshot 2023-04-26 141353](https://user-images.githubusercontent.com/121163440/234524000-20f18272-8cea-4f0e-a985-1ff052d84688.png)

### Output:
### RTL

![Screenshot 2023-04-26 141838](https://user-images.githubusercontent.com/121163440/234524090-02d6c6ba-93ba-4770-ac06-a997f37d3c3e.png)

![Screenshot 2023-04-26 141858](https://user-images.githubusercontent.com/121163440/234524181-369dd4f8-6ae5-4a8e-a306-a8acbe3b9494.png)


### TIMING DIAGRAM
![Screenshot 2023-04-26 141551](https://user-images.githubusercontent.com/121163440/234523892-7781f8de-966a-43b5-a2ed-f88d95089bd7.png)

TRUTH TABLE:


![Screenshot 2023-04-26 143019](https://user-images.githubusercontent.com/121163440/234525863-260e048c-2bea-4fe8-a376-de0c96eda033.png)


![Screenshot 2023-04-26 143028](https://user-images.githubusercontent.com/121163440/234525904-db8d41fc-93e3-46a4-93ce-b13711065b7f.png)


### Result:
 Thus the Implementation of Halfadder Fulladder Circuit are studied and the truthtable for
different logic gates are verified

