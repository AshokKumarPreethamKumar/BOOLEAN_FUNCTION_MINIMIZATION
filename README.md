# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2024-11-28 at 4 49 06 PM](https://github.com/user-attachments/assets/f6e767be-39b9-44d7-8a31-72668aba2738)


**Logic Diagram**


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. */

```
module exp2booleanfunctionminimization(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by:ASHOK KUMAR PREETHAM KUMAR

RegisterNumber:24002459


**RTL realization**

**Output:**

**RTL**

![Screenshot 2024-11-28 163747](https://github.com/user-attachments/assets/a5bee5f4-3333-4688-8955-3923befd2ee4)

**Timing Diagram**

![timing diagram exp2](https://github.com/user-attachments/assets/d8aa92cf-3a50-4379-8c15-5f16f92aada3)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

