# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

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
### Program: Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: SWETHA .A
RegisterNumber: 23003624 
## CODE:
##HALF ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/327cadcd-e976-4d7f-a4c2-3aa07fd64671)

##FULL ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/7aefea1e-f668-4dd6-be21-1b1e306b87b7)


##TRUTH TABLE:
##HALF ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/1119057b-3791-4f92-bf24-4f2ef0ff5f0c)

##FULL ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/edb409f5-e669-468a-b4de-3b382d107765)

##OUTPUT:
##RTL:
##HALF ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/eebc5d72-c37b-47fc-b11f-d92cf120a01f)

##FULL ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/f23def1a-f428-43f0-b58a-f0e5a36e86ee)

##TIMING DIAGRAM:
##HALF ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/1c2a5cd2-41a9-4797-930b-f5dc78678140)

##FULL ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/aab400c8-6177-4427-ba8a-6fd2fda8c1dc)


##TIMETABLE:
##HALF ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/cf68ed1f-5044-4bc3-84a5-7c93860f70fa)

##FULL ADDER:![image](https://github.com/aswethaashok/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149987410/375ec030-39c9-4fc7-a75e-a475d53a6088)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
