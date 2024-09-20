# EXPERIMENT--01-ALP-FOR-8086
Name :RADHIMEENA M

Roll no :212223040159

Date of experiment :12.08.24
## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color logo
 3. write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,DIVISION,AND,OR,NOT AND XOR operation
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
![image](https://github.com/user-attachments/assets/a6b88f89-e193-4050-a472-c5e63c584308)
8.Click on emulate to start emulation.	 
![image](https://github.com/user-attachments/assets/81bbc5eb-8a75-45b3-bd08-7ef9a76104da)
9.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 
![image](https://github.com/user-attachments/assets/d3a9bc65-0b9b-4db6-8069-f31168f8a80d)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 

```
MOV AL,88H
MOV BL,65H
ADD AL,BL
HLT
```

## Output  
 ![image](https://github.com/user-attachments/assets/492f06e4-ae6e-404f-8ec5-cd764384122d)

## Subtraction   of 8 bit numbers  ALP 
```
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
``` 
## Output  
![image](https://github.com/user-attachments/assets/194f9832-85a9-43d4-9225-d46e66d61f0c)

## Multiplication alp 
```
MOV AL,75H
MOV BL,32H
MUL BL
HLT
```
 ## Output  

![image](https://github.com/user-attachments/assets/6f911ced-b8d1-4450-af2e-70fa39a0f77b)

## Division alp 
```
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/5731581a-fdaa-4376-889e-742de73254a3)
## And of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## output
![image](https://github.com/user-attachments/assets/a947dd2b-6600-48db-8bf8-e809d850f8fd)

## OR of 8 bit numbers ALP 
```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## output
![image](https://github.com/user-attachments/assets/ca6aef8e-e7fe-47ad-99fe-7f6368006899)
## NOT of 8 bit number ALP
```
MOV AL,65H
NOT AL
HLT
```
## output
![image](https://github.com/user-attachments/assets/8eb6cf80-2001-45e4-968b-f9b4cbd12df9)

## XOR of 8 bit number ALP
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```
## output
![image](https://github.com/user-attachments/assets/cdfba449-9a56-46c1-8af0-7418b3e03522)
## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
