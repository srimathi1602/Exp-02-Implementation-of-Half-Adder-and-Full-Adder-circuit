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
Developed by:Srimathi M 
RegisterNumber: 212223050053 
*/
## HALF ADDER 
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/a868991e-55ed-4d58-bb80-96ef0262bdfb)

## FULL ADDER
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/396611e4-866f-4004-a0dc-eac7e6b7d053)

RTL realization
## HALF ADDER 
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/bbbb34b1-46e2-46fe-ad30-c3b7a96f3743)
## FULL ADDER
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/23929ea7-4a21-4849-a150-a5bb4431ea10)
TRUTH TABLE
## HALF ADDER 
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/06b68bee-d96b-47ed-9750-9eb71791bb02)

## FULL ADDER
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/e9c18a2b-9db4-44dc-8825-076b8b5a69ac)


### Output:
## HALF ADDER 
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/99513c1f-3a39-40ce-a14a-84f35e923332)

## FULL ADDER
![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/f132e692-dc95-4fff-a304-6d382ecbcbd5)

### Result:
