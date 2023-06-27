# Advanced-Scripting-Techniques-in-Design-and-Synthesis
## Contents</br>

## Day 1: Introduction to TCL and VSDSYNTH Toolbox Usage </br>

Section 1: Introduction </br>

Lecture 1: Introduction to TCL task</br>
Lecture 2: Introduction to sub-task</br></br>

Section 2: Sub-Task One: VSDSYNTH Toolbox usage scenarios</br>

Lecture 3: Scenario 1 - User doesn't provide an input CSV file</br>
Lecture 4: Scenarios 2 & 3 - User providing incorrect CSV or typing "-help"</br></br>

## Day 2: Variable Creation and Processing Constraints from CSV</br>

Section 3: Sub-Task Two - From CSV to format[1] and SDC - Variable Creation</br>

Lecture 5: Various tasks involved in format conversion</br>
Lecture 7: Auto-Create variables using matrix and arrays</br>
Lecture 8: Initialize variables for auto-creation variables task</br>
Lecture 9: Auto creation of the first variable - DesignName</br>
Lecture 10: Auto creation of variables complete</br>
Lecture 11: Variable Creation DEMO using TCL</br>
Section 4: Sub-Task Two - From CSV to format[1] and SDC - Processing constraints, CSV</br>

Lecture 12: Checking the existence of files and folders mentioned in design_details.csv</br>
Lecture 13: Convert constraints.csv file to a matrix object</br>
Lecture 14: Compute row number using complex matrix processing</br>
Lecture 15: DEMO for computing row numbers</br></br>

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
