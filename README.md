# EXPERIMENT--01-ALP-FOR-8086
Name :
Roll no 
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
mov ax,[1100h]
mov bx,[1102h]
add ax,bx
mov [1200h], ax
mov [1202h], dx
hlt
```
## Output  
<img width="1920" height="1080" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/3b1ac438-e5e1-467f-942f-b72998b9e420" />

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
sub ax,bx
mov [1200h],ax
mov [1202h],dx
hlt

```
 
## Output  
<img width="1920" height="1080" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/2a6f7ffe-6c86-4da8-a22e-cf9de825aed9" />

## Multiplication alp
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
mul bx
mov [1200h],ax
mov [1202h],dx
hlt
```
 ## Output  
<img width="1920" height="1080" alt="Screenshot (139)" src="https://github.com/user-attachments/assets/f8d84030-1aec-44c0-9ceb-9f4ef53e79c2" />


## Division alp 
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
div bx
mov [1200h],ax
mov [1202h],dx
hlt

```
## Output  
<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/c451cfb0-d302-499d-a3e2-621d135eee1b" />
## Programs for logical  operations
## OR ALP
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
or ax,bx
ret
```
## OUTPUT
<img width="1520" height="1128" alt="image" src="https://github.com/user-attachments/assets/3970b29b-75d7-4236-9a20-8f70ed6ce59b" />
## NOR ALP
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
or ax,bx
not ax
ret
```
## OUTPUT
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/9d713f54-a817-47c0-92af-b90fdf5d0cf1" />

## XNOR ALP
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
xor ax,bx
ret
```
## OUTPUT
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/e5b0563c-d247-416f-a617-32cd2b26fc81" />

## NOT ALP
```
org 100h
mov ax,[1100h]  
not ax 
ret
```
## OUTPUT
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/cfb4f0d1-ed88-4c0a-b803-8d3c601947bc" />

## Result :
Thus execution of ALP on fundamental arithmetic and logical operations is sucessfully verified.
 








