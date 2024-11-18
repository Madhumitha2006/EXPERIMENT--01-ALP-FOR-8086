# EXPERIMENT--01-ALP-FOR-8086
Name :MADHU MITHA V

Roll no: 2305002013

Date of experiment :
## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.
## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table.
8.	Click on emulate to start emulation

9.If no errors are found click on run the program and check the status of various flags in the flags tab as shown below.
## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
MOV AL,12H
MOV BL,10H
ADD AL,BL
HLT
## Output  
 ![Screenshot 2024-10-14 140818](https://github.com/user-attachments/assets/842a43a6-9ae3-463b-a132-2d18019d80e3)

## Subtraction of 8 bit numbers  ALP 
MOV AL,12H
MOV BL,10H
SUB AL,BL
HLT
## Output 
![Screenshot 2024-10-14 140917](https://github.com/user-attachments/assets/e6f002ce-6685-46c6-8b1d-4728c5ceae52)

## Multiplication of 8 bit numbers  ALP 
MOV AL,12H
MOV BL,10H
MUL BL
HLT
 ## Output  
![Screenshot 2024-10-14 141032](https://github.com/user-attachments/assets/03c4d48f-5318-4a5b-b606-0ff51ab80188)

## Division of 8 bit numbers  ALP 
MOV AL,12H
MOV BL,2H
DIV BL
HLT
## Output  
![Screenshot 2024-10-14 141219](https://github.com/user-attachments/assets/0245c1e3-b5ce-436e-8b8b-816728f02f42)

## AND of 8 bit numbers  ALP 
MOV AL,12H
MOV BL,22H
AND AL,BL
HLT
## Output 
![Screenshot 2024-10-14 141439](https://github.com/user-attachments/assets/a5e51856-ada7-442f-88f3-9dee2e7b715c)

## OR of 8 bit numbers  ALP 
MOV AL,12H
MOV BL,22H
OR AL,BL
HLT
## Output
![Screenshot 2024-10-14 141523](https://github.com/user-attachments/assets/3d0cec7d-3d91-401f-8daa-1915c7cf66c2)

## NOT of 8 bit numbers  ALP 
MOV AL,12H
NOT AL
HLT
## Output
![Screenshot 2024-10-14 141630](https://github.com/user-attachments/assets/eb10d964-1647-4aba-b458-328357994014)

## XOR of 8 bit numbers  ALP 
MOV AL,12H
MOV BL,16H
XOR AL,BL
HLT
##Output

![Screenshot 2024-10-14 141740](https://github.com/user-attachments/assets/0e5a531b-03e8-4c1c-9b59-f47df3c7b6a8)


## Result : The program to Write and execute ALP on fundamental arithmetic and logical operations is executed.
 








