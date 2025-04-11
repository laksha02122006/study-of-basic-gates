### study-of-basic-gates
## Date : 14/3/25
**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming
module ex1 (a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output  y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a);
nand(y4,a,b);
nor(y5,a,b);
xor(y6,a,b);
xnor(y7,a,b);
endmodule

 Developed by: V.B.Laksha
 
 RegisterNumber: 212224220051
 
**Logic symbol & Truthtable**
AND gate
![Screenshot 2025-03-21 091858](https://github.com/user-attachments/assets/041cae18-a290-4b6e-a890-21fd2a924c5a)
OR gate
![Screenshot 2025-03-21 092011](https://github.com/user-attachments/assets/1bf0b1e1-587b-414f-af63-557b95ba6325)
NOT gate
![Screenshot 2025-03-21 092029](https://github.com/user-attachments/assets/d92b4680-e284-4e11-8761-c2c3b380a96c)
NAND gate
![Screenshot 2025-03-21 092220](https://github.com/user-attachments/assets/5dbd5aeb-84a4-45b7-b0dd-944251ac526e)

NOR gate
![Screenshot 2025-03-21 092158](https://github.com/user-attachments/assets/87c8bdb8-c935-44de-8dd9-95d8ebd6f5bf)

XOR gate
![Screenshot 2025-03-21 092238](https://github.com/user-attachments/assets/dc85f1c9-4854-44fd-a74a-68dc6a7bba06)
XNOR gate
![Screenshot 2025-03-21 092257](https://github.com/user-attachments/assets/b83e2ba8-2f90-4641-9273-b6441abada8e)

**RTL realization Output:** 

![Screenshot (38)](https://github.com/user-attachments/assets/1dabbc74-621a-4183-9477-2a9271b9e571)

**RTL**
![Screenshot (40)](https://github.com/user-attachments/assets/5f2df3f5-4ba7-4458-986b-28d437d2356d)

**Result:**
Thus the Basic digital ICs and the verification of truth tables for different logic gates were studied and successfully realized using Verilog.


