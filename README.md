# Real_Time_and_Embedded_Systems
# 0 to 99 counter
This is an Embedded C program to display numbers from 0 to 99 on two 7 segment displays by using AT89C51 microcontroller. I 
have used Keli uVision5 IDE to build the C source code and Proteus for running the simulation. On the program two 7 segm
ent display Anodes and AT89C51 microcontroller were used.
# How to run the program? 
In the folder of the project, you will find 7_Segment.c -> C source code, 7_Segment_Display_2digits.uvproj -> the project containing source code and 7_segment_Display_2_Digits_simu.pdsprj -> the simulation of the project. First open the project file (7_Segment_Display_2digits.uvproj) in Keli uVision5 IDE (or your preferred IDE) and find the source code in the project. Build the C source code to generate a HEX file. The generated HEX file can be found in "Objects" folder in the parent folder where the project is located. After that, open the 7_segment_Display_2_Digits_simu.pdsprj using Proteus ( or your preferred simulation software) to see the simulation of the program and to attach the generated Hex file. To attach the HEX file, double click on the microcontoller and find and option that says "Program File", on the right side you will see
a "browse" folder. Click on that, find the hex file in the "objects" folder and select it. After that click on ok to save
the progress. The "Edit Component" dialog box is closed and the HEX file will be attached successfully. 
This HEX file is very improtant for the simulation to function as it serve as an interface for connecting the source code 
with simulation. After linking the HEX file you can run the simlation to see the two 7 segment displays ("7SEG-COM-ANODE"
in technical terms) count from 00 to 99.
The two 7 segment display are positioned side to side. The left and the right 7SEG-COM-ANODE displays the left and right 
digits respectively while maintaing the operation simultaneously. 
# Where to apply the project?
This counter can be practically used for the change of Traffic light from one light to another. For instance to change the
light from Green to red we can use the counter by setting the countdown to a favourable number.

