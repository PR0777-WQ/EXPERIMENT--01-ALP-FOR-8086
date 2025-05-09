# EXPERIMENT 01 ALP FOR 8086
Name : G Nitin karthikeyan

Roll no : 212224040227







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


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h 
MOV AX,1400H 
MOV BX,1400H
ADD AX,BX
ret
```
## Output  
![Screenshot 2025-03-04 102445](https://github.com/user-attachments/assets/e7a4fed1-30b7-48cb-97df-55b1ae91ea4a)

## Subtraction   of 8 bit numbers  ALP 
```
org 100h 
MOV AX,[5000h] 
MOV BX,[5002h]
SUB AX,BX
ret
```
## Output  
![Screenshot 2025-03-04 104032](https://github.com/user-attachments/assets/dd7bd25b-2906-48e5-8283-bbc9c4b83c17)

## Multiplication alp 
```
org 100h 
MOV BX,1234H
MOV CX,123H 
MOV AX,CX
mul BX
ret
```
## Output  
![Screenshot 2025-03-04 105049](https://github.com/user-attachments/assets/8ec4a23a-a90a-4ef0-989c-d942acac7db9)


## Division alp 
```
org 100h 
MOV BX,50H
MOV AX,BX
MOV CX,05H
DIV CX
ret
```
## Output  
![Screenshot 2025-03-04 111617](https://github.com/user-attachments/assets/a965d8bc-d644-4986-9a73-2c02e61967dd)

## And of 8 bit numbers ALP
```
org 100h
MOV AL,33H
MOV BL,44H
AND AL,BL
ret
```
## Output
![Screenshot 2025-03-11 105200](https://github.com/user-attachments/assets/28facc72-1890-4e76-bf59-5fe34f2763ea)

## OR of 8 bit numbers ALP
```
org 100h
MOV AL,45H
MOV BL,66H
OR AL,BL
ret
```
## Output
![Screenshot 2025-03-11 105536](https://github.com/user-attachments/assets/ca2915c8-420e-4d14-971b-dfa3faa443c0)

## NOT of 8 bit number ALP
```
org 100h
MOV AL,65H
NOT AL
ret
```
## Output
![Screenshot 2025-03-11 105834](https://github.com/user-attachments/assets/c6b72a97-33e8-41f9-ad60-3dfb45139269)

## XOR of 8 bit number ALP
```
org 100h
MOV AL,66H
MOV BL,77H
XOR AL,BL
ret
```
## Output
![Screenshot 2025-03-11 110039](https://github.com/user-attachments/assets/df7ebef2-fd6d-4e46-8f6a-33553fe40283)

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







