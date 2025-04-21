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
FULL ADDER:
![Screenshot 2024-04-01 194127](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/b2f3f217-76b3-4f12-a7ba-54b5ff8b4838)
FULL SUBRACTOR:
![Screenshot 2024-04-01 194137](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/b0b7195c-e9a1-4ebf-a594-72a65835e8b2)



**Procedure**

STEP 1: Use module project name(input,output) to start the Verilog programmming. 
STEP 2: Assign inputs and outputs using the word input and output respectively. 
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression. 
STEP 4: Use each output to represnt onre for differnce and the other for borrow. 
STEP 5: End the verilog program using keyword endmodule.

**Program:**
```
DEVELOPED BY: ROSHAN G
REGISTER NO: 212223040176
```
![Screenshot 2024-04-01 194146](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/379aef4f-5d02-4e49-acd2-9bdbe7391808)
![Screenshot 2024-04-01 194154](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/42baaa46-0fb3-43f8-9c61-7025ae54e0e0)





**RTL Schematic**
![Screenshot 2024-04-01 194203](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/c56fbbea-084b-4a25-a1af-893635e8e8cd)
![Screenshot 2024-04-01 194211](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/6bc0e1a2-bc9c-46df-ab7f-0ffd68cd061d)



**Output Timing Waveform**
![Screenshot 2024-04-01 194222](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/b6aa2dc0-3c90-48c6-a54e-43bf869a17ce)
![Screenshot 2024-04-01 194230](https://github.com/PREM3112/FULL_ADDER_SUBTRACTOR/assets/145449383/44f71d89-0fc5-4dfc-915a-0363c0c87dda)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



