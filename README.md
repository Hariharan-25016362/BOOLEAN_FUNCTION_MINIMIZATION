# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
F1
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
F2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by: HARIHARAN M RegisterNumber:25016362


**RTL realization**
F1
<img width="1760" height="946" alt="Screenshot 2025-11-29 114631" src="https://github.com/user-attachments/assets/97518157-1f1c-4cb0-a5c7-9b7347069105" />
F2
<img width="1783" height="921" alt="Screenshot 2025-11-29 114711" src="https://github.com/user-attachments/assets/a727ed19-5a6f-4ad2-bb6c-3c1057948f6a" />



**Output:**
F1
<img width="1916" height="737" alt="Screenshot 2025-11-29 113656" src="https://github.com/user-attachments/assets/aca66e6a-a139-4045-8bfb-1d7abfe8e2ca" />
F2
<img width="1914" height="601" alt="Screenshot 2025-11-29 114125" src="https://github.com/user-attachments/assets/a4d62292-37d3-4256-925e-bfa92fdb7633" />






**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

