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

Developed by: NIRANJAN S
RegisterNumber:24900209
~~~
module boolean_functions (
    input a, b, c, d, // Inputs for f1
    input w, x, y, z, // Inputs for f2
    output f1, f2     // Outputs
);

endmodule
~~~

**RTL realization**
![398050237-5655f823-98ae-4540-abee-874651eac3da](https://github.com/user-attachments/assets/5ccbaae4-c507-4984-8359-bc7ff3683125)

**Output:**
**Timing Diagram** 
![398050467-d60690e2-a159-4c73-98c9-045d505f7da3](https://github.com/user-attachments/assets/45272ba4-d5fb-43f7-b147-a7f0955d09f2)

![398050453-addcc60a-bb4d-427d-8c19-3d6131776460](https://github.com/user-attachments/assets/31ead6d6-f79c-46db-94b3-af5f747cc2ca)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

