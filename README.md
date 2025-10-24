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
<img width="400" height="574" alt="Screenshot 2025-10-23 205001" src="https://github.com/user-attachments/assets/a870c4a9-e0e2-47df-9622-c14851b48a86" />

**Procedure**

Write the detailed procedure here
 1.Type the program in Quartus software.
 2.Compile and run the program.
 3.Generate the RTL schematic and save the logic diagram.
 4.Create nodes for inputs and outputs to generate the timing diagram.
 5.For different input combinations generate the timing diagram
**Program:**
 1.Type the program in Quartus software.
 2.Compile and run the program.
 3.Generate the RTL schematic and save the logic diagram.
 4.Create nodes for inputs and outputs to generate the timing diagram.
 5.For different input combinations generate the timing diagram
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:VISHAL R RegisterNumber:25004464
*/
Full Adder:

<img width="873" height="249" alt="Screenshot 2025-10-24 095532" src="https://github.com/user-attachments/assets/3fdaf6e2-8aac-406c-a936-cabc91f402f0" />
Full Subtractor:

<img width="790" height="305" alt="Screenshot 2025-10-24 095542" src="https://github.com/user-attachments/assets/dfc28f55-5ca4-4e91-9121-ee60c285f16f" />

**RTL Schematic**
<img width="542" height="352" alt="Screenshot 2025-10-23 205142" src="https://github.com/user-attachments/assets/3c66f095-8ef8-4d93-aec8-d263c3a2552f" />

**Output Timing Waveform**
<img width="555" height="638" alt="Screenshot 2025-10-23 205224" src="https://github.com/user-attachments/assets/dec20c60-a5d3-452d-817a-790c61615af3" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



