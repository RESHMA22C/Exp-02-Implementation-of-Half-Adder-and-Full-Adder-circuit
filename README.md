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
Developed by: RESHMA C
RegisterNumber: 23012886  
*/
Code:
![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/447b8e4b-04bb-4f4a-b552-032daddc7f3f)

![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/5a864886-39f1-478c-9fa3-55366324ff5f)


### Output:
![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/ea06abfa-d148-4700-bf91-2284c9ff7bbb)

![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/2b718ddd-cf2f-4ef7-940e-d980a531511f)



### RTL:
![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/c82cb4a5-d552-4691-b146-4dc335b2b96e)
![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/179fa019-f66d-46db-9eb5-48cd3048d316)


### TIMING DIAGRAM:

![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/e1ee915a-32e4-47be-86e3-7088040df6fd)


![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/9ccd853a-d5fa-44a8-b193-cdd994e08ee3)



### TRUTH TABLE ;
![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/520285bf-ef87-4b23-ad95-dbd812d3c55c)

![image](https://github.com/RESHMA22C/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474426/4e6d8139-230d-47d0-8ad4-742c18336471)

### Result:
Thus the half adder and full adder circuits are designed and the truth table is verified using quartus software
