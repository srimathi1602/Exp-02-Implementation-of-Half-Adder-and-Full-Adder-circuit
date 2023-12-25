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
Developed by: 
RegisterNumber:  
*/
### HALF ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/75515bab-f636-48f6-94ee-1b0f16329daa)

### FULL ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/765a5d96-0921-47e2-98d6-a57b97a5e7c4)

RTL realization
### HALF ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/c7a84c8d-2b87-4146-a1ba-05688d249c7b)

### FULL ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/a1046f2b-1a75-4fa4-9e7f-22b1d57a0d0b)

### TRUTH TABLE 
### HALF ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/e24a849c-1559-4a08-b2f9-28a32dbb2ea5)

### FULL ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/222de92e-dd03-4d91-8a0a-38d7942e01a5)

### OUTPUT
### HALF ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/b078dae1-0e35-42b6-8287-d85ac80de0fa)

### FULL ADDER
![image](https://github.com/srimathi1602/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153518608/c740cce4-fe41-4fb3-ab76-de1fc9bb7b3f)
### Result:
