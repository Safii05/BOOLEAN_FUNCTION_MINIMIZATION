# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-29 at 10 50 38 AM](https://github.com/user-attachments/assets/bc2bc995-a312-4b86-8c5c-e3b7aa77151f)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by:Safira barveen s RegisterNumber:24900731


**RTL realization**



**Output**
Uploading exp2.jpg…]()




**RTL**
![exp2](https://github.com/user-attachments/assets/46f257ca-472e-4a1b-957d-e6a41c4b3e6d)



**Timing Diagram**
![Screenshot 2024-10-22 114356](https://github.com/user-attachments/assets/afe644b7-2057-4cdc-9663-eba072082e00)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

