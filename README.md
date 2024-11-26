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
~~~
**Program:**
i)
module EXPERIMENT2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
ii) 
module exp21(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: vishal s
RegisterNumber:24008833
~~~

**RTL realization**
![Screenshot 2024-11-26 180240](https://github.com/user-attachments/assets/59075150-009f-436c-b806-98835485de4b)
![Screenshot 2024-11-26 181437](https://github.com/user-attachments/assets/ed97b6e2-1d21-4459-9025-e311378c9417)


**waveform**
![Screenshot 2024-11-26 180905](https://github.com/user-attachments/assets/09d77a97-38ac-4139-ac0d-ec003f94eab1)
![Screenshot 2024-11-26 181713](https://github.com/user-attachments/assets/760fc778-7239-49ba-bda3-cc6b4f6be000)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

