# Advanced-Scripting-Techniques-in-Design-and-Synthesis

Lecture 1: Introduction to TCL task </br>
</br>
The task is to take a User Interface to take an Excel file as an input and provide the output as a datasheet. </br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/d854fc7c-2961-4f39-bad0-c55c524c2a40)

Checking the contents of the CSV file</br>
</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/6d15afa1-8e5c-447e-bc84-6f618b78ffa4)</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/6d63c62b-d393-4772-a1b7-9e1bada86e74)</br>


Lecture 2: Introduction to sub-task
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/ff578704-857b-4b6e-8bb4-c9051f6e2988)</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/702b5843-2fff-439f-93af-632cd6bc62c9)</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/8bb1a14c-763f-44e0-895a-a83feee8e2cf)</br>

 
</br>
 
YOSYS tool will help to synthesize the design.</br>
</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/b5f6337b-a6dc-4a9c-8f2b-d934c22583a4)</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/021a98b3-4a88-48a2-8b18-dd070204b9a7)</br>


Convert csv file into an SDC file. (Creating input and output ports)</br>
</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/7fc06c42-7661-46d9-b5ac-6fcb3a5156b4)</br>

OpenTimer is used to create the datasheet or performance chart.</br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/3a2f715c-6975-41ad-965d-cdf68084a842)</br>
</br>


Section 2: Sub-Task One: VSDSYNTH Toolbox usage scenarios </br>
Lecture 3: Scenario 1 – The user doesn't provide an input CSV file </br>
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/48ae8ba8-b681-49fd-a525-e2f5082b0ed7)
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/b89992a9-2ee3-4848-a353-94bd77a51817)
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/88ce2f6b-112e-4e23-8a6a-b8e5a79a6a3d)

 
CSV file not provided.
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/71ffaba3-4226-4f65-ba72-893b7b19fb92)


Lecture 4: Scenarios 2 & 3 - User providing incorrect CSV or typing "-help."
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/239652c4-f678-4085-8e8f-1a651e826517)
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/0c53401c-3707-4702-84ea-498bfdd269a6)

 
Checking incorrect CSV file
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/b625c8b1-3e01-46cc-8d32-4bd87c9753c3)
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/5d469363-95a3-4141-97fd-745757183edc)
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/0181ed72-6d25-46bd-97c9-6ddcd9c4c064)

 
 
Creating “-help” for user guidance
![image](https://github.com/srsapireddy/Advanced-TCL-Scripting/assets/32967087/7e226a4d-a6bc-4496-a39e-f5d308a5ecb9)


Day 2: Variable Creation and Processing Constraints from CSV
Lecture 5: Various tasks involved in format conversion.
 
 
 
 
 
 

Lecture 6: Auto-Create variables using matrix and arrays.
 
Set filename [lindex $argv 0]
 


Lecture 7: Initialize variables for auto-creation variables task.










 

 
 
MAP FILE TO MATRIX
 
 
 
 
 
 

 

Lecture 8: Auto creation of the first variable – DesignName
 
 
 
$DesignName = openMSP430






Lecture 9: Auto creation of variables complete.
 
 
 
 
Mapping the matrix to the matrix. Then mapping matrix variables to a CSV file.
 


Lecture 10: Variable Creation DEMO using TCL.
 
 
Checking the auto-creation of the variables
 

Section 4: Sub-Task Two - From CSV to format[1] and SDC - Processing constraints, CSV
Lecture 12: Checking the existence of files and folders mentioned in design_details.csv
 
 
 
 
 

Lecture 13: Convert the constraints.csv file to a matrix object.
 
 
 
 
 
Lecture 14: Compute row numbers using complex matrix processing.
 
 
 
 
 
Lecture 15: DEMO for computing row numbers
 
 
 


## Day 3: Processing Clock and Input Constraints</br>


Section 5: Sub-Task Two - From CSV to format[1] and SDC - Processing clock constraints</br>

Lecture 16: Algorithm to identify the column number for clock latency constraints</br>
Lecture 17: Start writing clock latency constraints in the SDC file</br>
Lecture 18: Complete clock latency constraints and clock slew constraints in the SDC file</br>
Lecture 19: Code to create clock constraints with clock period and duty cycle</br>
Lecture 20: DEMO for creating complete clock constraints</br>

Section 6: Sub-Task Two - From CSV to format[1] and SDC - Processing input constraints</br>

Lecture 21: Introduction to the task of differentiating between bits and a bus</br>
Lecture 22: Algorithm to categorize input ports as bits and bussed</br>
Lecture 23: File access and pattern creation steps</br>
Lecture 24: Regular expression and regular substitute to get fixed space strings</br>
Lecture 25: Demo for grepping input ports from all verilogs and reformatting for fixed space</br>
Lecture 26: Read, split, uniquify, sort, and join input ports to remove duplication</br>
Lecture 27: Evaluate the length of the string and Demo of bits/bussed differentiation script</br>
Lecture 28: Demo for input constraints generation and bits/bussed differentiation</br></br>

## Day 4: Complete Scripting and Yosys Synthesis Introduction</br>

Section 7: Full script for download and Conclusion</br>

Lecture 29: Constraints generation logic for the output port and Conclusion!!</br>
Section 8: Introduction to Yosys synthesis tool usage</br>

Lecture 2: Example of a memory module RTL description</br>
Lecture 3: Memory functionality and Synthesis using Yosys</br>
Lecture 4: Components and Gate level netlist description of Synthesized memory</br>
Lecture 5: Memory Write operation discussed in detail</br>
Lecture 6: Memory Read operation and TCL scripting agenda</br>
Section 9: Hierarchy check and error handling script creation for Yosys</br>

Lecture 7: Script to do a hierarchy check</br>
Lecture 8: Demo for hierarchy check script generation</br>
Lecture 9: Demo for error handling concept in hierarchy check</br>
Lecture 10: Error handling script for hierarchy check</br>
Lecture 11: Demo for error handling script</br></br>

## Day 5: Advanced Scripting Techniques and Quality of Results Generation</br>

Section 10: Synthesis main file scripting and output file editing</br>

Lecture 12: Synthesis script creation and demo</br>
Lecture 13: Need and script to edit Yosys output netlist</br>
Lecture 14: Demo to edit output netlist and Introduction to 'procs'</br>
Section 11: World of 'Procs'</br>

Lecture 15: Redirect stdout proc and demo of TCL array command</br>
Lecture 16: 'set_multi_cpu_usage' proc</br>
Lecture 17: Demo for 'set_multi_cpu_usage' proc</br>
Lecture 18: read_lib and read_verilog proc demo</br>
Section 12: read_sdc proc - interpret clock generation constraints</br>

Lecture 19: Read SDC file and replace square brackets by 'null'</br>
Lecture 20: Evaluate clock period and clock port name from processed SDC</br>
Lecture 21: Evaluate duty cycle and create clock in opentimer format</br>
Lecture 22: Demo to convert constraints from SDC format to opentimer format</br>
Section 13: read_sdc proc - interpret IO delays and transition constraints</br>

Lecture 23: Grep clock latency and port name from SDC file</br>
Lecture 24: Convert set_clock_latency SDC to opentimer format</br>
Lecture 25: Demo to convert set_clock_latency in SDC to arrival_time in opentimer</br>
Lecture 26: Script and demo convert transition and input delay to opentimer format</br>
Lecture 27: Script and demo to convert output SDC constraints to opentimer format</br>
Section 14: Process bussed ports and configuration file creation</br>

Lecture 28: Script to expand bussed input ports for arrival time constraints</br>
Lecture 29: Script and demo to convert all bussed constraints to bit-blasted</br>
Lecture 30: Opentimer configuration file creation</br>
Section 15: Quality of results (QOR) generation algorithm</br>

Lecture 31: Script to obtain STA runtime</br>
Lecture 32: Script to obtain WNS and FEP for reg2out violations</br>
Lecture 33: Script and demo for instance count, WNS, and FEP for setup and hold</br>
Lecture 34: Script and demo for report formatting</br>
Section 16: Conclusion</br>

Lecture 35: Conclusion and acknowledgments</br>
