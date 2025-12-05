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

i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by: vinutha v
RegisterNumber:25017424 


**RTL realization**

<img width="1796" height="949" alt="Screenshot 2025-12-05 185549" src="https://github.com/user-attachments/assets/9e6c1741-2ae5-4fae-a6d0-7c2fceb0962a" />
<img width="1704" height="931" alt="Screenshot 2025-12-05 190045" src="https://github.com/user-attachments/assets/e9726ba2-607c-47ef-b515-a3ab129a57a5" />


**RTL**
<img width="1907" height="987" alt="Screenshot 2025-12-05 185445" src="https://github.com/user-attachments/assets/f4975bd5-9694-42d4-814f-c0048e18ab65" />
<img width="1908" height="927" alt="Screenshot 2025-12-05 192221" src="https://github.com/user-attachments/assets/1e1cd173-a672-42cf-aedf-4a982e240614" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

