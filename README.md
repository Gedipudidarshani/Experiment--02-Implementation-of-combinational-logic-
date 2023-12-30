# Date:
# Exp-02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 #Name:Gedipudi Darshani
 #Register Number:212223230062
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
 Hardware – PCs, Cyclone II , USB flasher
 Software – Quartus prime


## Theory
 A combinational circuit is a circuit in which the output depends on the present
combination of inputs.
Combinational circuits are made up of logic gates. The output of each
logic gate is determined by its logic function. Combinational circuits can
be made using various logic gates, such as AND gates, OR gates, and
NOT gates.


## Procedure:
1.Create a New Project:
Open Quartus and create a new project by selecting &quot;File&quot; &gt; &quot;New Project
Wizard.&quot;
Follow the wizard&#39;s instructions to set up your project, including
specifying the project name, location, and target device
(FPGA).
2.Create a New Design File:
Once the project is created, right-click on the project name in the
Project Navigator and select &quot;Add New File.&quot;

Choose &quot;Verilog HDL File&quot; or &quot;VHDL File,&quot; depending on your
chosen hardware description language.
3.Write the Combinational Logic Code:
Open the newly created Verilog or VHDL file and write the code for your
combinational logic.
4.Compile the Project:
To compile the project, click on &quot;Processing&quot; &gt; &quot;Start Compilation&quot; in the
menu.
Quartus will analyze your code, synthesize it into a netlist, and
perform optimizations based on your target FPGA device.
5.Analyze and Fix Errors:
If there are any errors or warnings during the compilation process,
Quartus will display them in the Messages window.
Review and fix any issues in your code if necessary.
View the RTL diagram.
6.Verification:
Click on &quot;File&quot; &gt; &quot;New&quot; &gt; &quot;Verification/Debugging Files&quot; &gt; &quot;University Program
VWF&quot;.
Once Waveform is created Right Click on the Input/Output Panel &gt; &quot;
Insert Node or Bus&quot; &gt; Click on Node Finder &gt; Click On &quot;List&quot; &gt; Select All.
Give the Input Combinations according to the Truth Table amd then simulate the
Output Waveform.

## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by:Gedipudi Darshani 
RegisterNumber: 212223230062

![image](https://github.com/Gedipudidarshani/Experiment--02-Implementation-of-combinational-logic-/assets/139340574/390f670f-97bb-4ad8-9273-63afa501878e)

*/
## RTL realization
![image](https://github.com/Gedipudidarshani/Experiment--02-Implementation-of-combinational-logic-/assets/139340574/a788eebe-c7b4-4ffe-aa34-c768d385a6ca)

## Output:

## Truth Table
![image](https://github.com/Gedipudidarshani/Experiment--02-Implementation-of-combinational-logic-/assets/139340574/1a2a6d2f-f143-4d00-a229-900307e24855)

## Timing Diagram
![image](https://github.com/Gedipudidarshani/Experiment--02-Implementation-of-combinational-logic-/assets/139340574/5e81ab76-0ebb-4adb-bd9a-a6630504e281)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
