### Name : JEFFY BRAILIN T
### Roll no : 212223040076
# EXPERIMENT 01 ALP FOR 8086
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
mov ax,26h;
mov bx,09h;
add ax,bx;
mov [2609h],ax;
ret
```

## Output  
![add 1st](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/b00d9969-c0d0-467e-83cf-7120614449f9)

 
## Subtraction   of 8 bit numbers  ALP 

```
org 100h
mov ax,26h;
mov bx,09h;
sub ax,bx;
mov [2609h],ax;
ret
```
## Output  
![sub 2nd](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/ecefae9a-eee0-46f0-ac6c-f785385d0b39)

## Multiplication alp 
```
org 100h
mov ax,26h;
mov bx,09h;
mul bx;
mov [2609h],ax;
ret
```
 ## Output  
![mul 3rd](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/ce186be2-d352-491b-a5d5-31343afa1609)

## Division alp 
```
org 100h
mov ax,26h;
mov bx,09h;
div bx;
mov [2609h],ax;
ret
```
## Output  
![div 4th](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/5674ddfd-9ed1-49d2-acfd-b87b4c890311)
## Programs for logical operations
## AND
org 100h
mov AL,66h;
mov BL,70h;
AND AL,BL;
HLT
ret
## Output
![image](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/407b6d2f-c9b1-4d05-97d2-ed058777ddeb)
## OR
org 100h
mov AL,66h;
mov BL,70h;
OR AL,BL;
HLT
ret
## Output
![image](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/4b573237-c7ff-484c-804f-ca3daafb395b)
## NOT
org 100h
mov AL,66h;
NOT AL;
HLT;
ret
## Output
## XOR
org 100h
mov AL,66h;
mov BL,70h;
XOR AL,BL;
HLT
ret
## Output
![image](https://github.com/jeffybrailin/EXPERIMENT--01-ALP-FOR-8086/assets/146911326/333997b9-12df-49e2-b7b4-7a2b0cad3790)

## Result :
 Thus, to write and execute ALP on fundamental arithmetic operations is successful.








