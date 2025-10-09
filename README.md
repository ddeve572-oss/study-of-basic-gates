### VERIFICATION OF LOGIC GATES

**AIM**

To develop the source code for logic gates by using VERILOG and obtain the simulation, synthesis, place and route and implement into FPGA.

**ALGORITHM**

Step1: Define the specifications and initialize the design.
Step2: Declare the name of the entity and architecture by using VHDL source code.
Step3: Write the source code in VERILOG.
Step4: Check the syntax and debug the errors if found, obtain the synthesis report.
Step5: Verify the output by simulating the source code.
Step6: Write all possible combinations of input using the test bench.
Step7: Obtain the place and route report. 


**VERILOG SOURCE CODE**

module logicgates1(a, b, c);
    input a;
    input b;
    output  [6:0] c;

	assign c[0]= a & b;
	assign c[1]= a | b;
	assign c[2]= ~(a & b);
	assign c[3]= ~(a | b);
	assign c[4]= a ^ b;
	assign c[5]= ~(a ^ b);
	assign c[6]= ~ a;

endmodule
**Logic symbol & Truthtable**

![image ](https://github.com/user-attachments/assets/92c7ea18-597f-4c83-936d-c52e162274e0)

**RTL realization Output:** 
![image ](https://github.com/user-attachments/assets/11f6f1a2-15f8-4a08-8a69-14151d8819bb)

**RTL**
**Result:**
Thus the outputs of Basic Logic Gates are verified by simulating and synthesizing the VERILOG code.


this is developed by : DEVENDRAN.G
roll no : 25008564





