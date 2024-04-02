# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
Truthtable FULL ADDER:
![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/a62a3ae7-96ff-4d32-b4fd-90214af5c6ae)
FULL SUBRACTOR:
![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/0c4eeea8-10fe-4949-bbef-6b1ee99fdefe)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.
6.	


**Program:**
![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/17bf86d3-e0c7-44bd-a969-09446493fa7d)

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/b825d1cc-5620-4a3b-9139-2a49be5999a7)



Developed by:Praveen K

RegisterNumber:212223230153

**RTL Schematic**
![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/ef78022f-c87c-4bcc-926e-340575ce481c)

**Output/TIMING Waveform**
![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/f22c6ffb-34c8-4542-adcb-96bd1c233934)

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/145742724/b7161c65-0c5e-4935-9124-3cf04e14e0f0)

**Result:**
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.


