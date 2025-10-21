# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic** 
FULL ADDER :
<img width="1918" height="1078" alt="EXP04 FULL ADDER " src="https://github.com/user-attachments/assets/f15e0047-9def-44fe-9625-03dd3afc3b24" />

FULL SUBTRACTOR : 
<img width="1918" height="1078" alt="EXP4 FULL SUBTRACTOR" src="https://github.com/user-attachments/assets/9bed2679-89c0-4e8d-b320-1285782e47b9" />

**Output Timing Waveform**
FULL ADDER :
<img width="1918" height="1078" alt="EXP04 FULL ADDER clock diagram" src="https://github.com/user-attachments/assets/9f0851a5-9f64-49ed-bbda-d84a74cc8646" />

FULL SUBTRACTOR :
<img width="1918" height="1078" alt="EXP4 FULL SUBTRACTOR CLOCK DIAGRAM" src="https://github.com/user-attachments/assets/eb7ec42c-5296-498e-b89b-efb6635310c2" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



