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
Full adder
![Screenshot 2024-12-08 115428](https://github.com/user-attachments/assets/0c0e93ad-8cf4-440d-ba4f-bd65bfe835b7)

Full subtractor
![Screenshot 2024-12-08 115857](https://github.com/user-attachments/assets/7d66a1c7-2950-4108-b6ed-cce49fb8c7d5)


**Procedure**

Write the detailed procedure here

**Program:**
Full adder
![Screenshot (57)](https://github.com/user-attachments/assets/c43d3c46-998d-4bee-bc13-4610ff7a7e22)
Full subtractor
![Screenshot (59)](https://github.com/user-attachments/assets/1c91b3d5-ca64-4f01-a34f-f0b274d5ea85)



/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: SANTHOSH S 
RegisterNumber: 24004753
*/

**RTL Schematic**
Full adder
![Screenshot (58)](https://github.com/user-attachments/assets/951c4928-d247-41cb-babb-41eb4cfad139)
Full subtractor
![Screenshot (60)](https://github.com/user-attachments/assets/97607fa9-9b53-44ec-b48c-ede7913bf724)



**Output Timing Waveform**
Full adder
![Screenshot (56)](https://github.com/user-attachments/assets/49a63365-db50-4315-bd4e-beba348402f3)
Full subtractor
![Screenshot (61)](https://github.com/user-attachments/assets/e4819e1c-66d3-46f4-ab41-1db0d6e101db)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



