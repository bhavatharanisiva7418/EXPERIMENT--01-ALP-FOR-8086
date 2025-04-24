# EXPERIMENT--01-ALP-FOR-8086
Name :BHAVATHARANI S
Roll no :212223230032
Date of experiment :24-04-20205





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
mov ax,1560h;
mov bx,0123h;
add ax,bx;
mov [1234h],ax;
ret
```

## Output  
 ![Screenshot 2025-04-24 140150](https://github.com/user-attachments/assets/3d473dc4-c91e-4747-a671-31aee02c7c88)

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
mov ax,2978h;
mov bx,3781h;
sub ax,bx;
mov [4678h],ax;
ret
```
## Output  
![image](https://github.com/user-attachments/assets/e7c5d3d2-86d3-4dd3-9720-568ce284fd40)

## Multiplication alp
```
org 100h
mov ax,4028h;
mov bx,3421h;
mul ax;
mov [4004h],ax;
ret
```
 ## Output  
![image](https://github.com/user-attachments/assets/28aab1af-e3ad-4e63-b6bb-741fa4bdcb3b)

## Division alp 
```
org 100h
MOV al,23h;
MOV bl,[2956h];
DIV bl;
MOV [2956h],al;
ret
```
## Output  
![image](https://github.com/user-attachments/assets/418744a6-a1ae-4d69-afe9-86e764034157)

## AND Operation
```
org 100h

mov SI,0532h;
mov ax,0A24h;
mov bx,0b14h;
and ax,bx; 
mov [0007h],ax;
ret
```
## Output
![image](https://github.com/user-attachments/assets/eb5191d8-bd2d-4b87-a11f-b3318e42e472)

## OR Operation
```
org 100h
mov [SI+2],ax;
mov ax,0A42h;
not ax
xor ax,bx; 
mov [0008h],ax;
ret
```
## Output
![image](https://github.com/user-attachments/assets/e34c6ee4-4ed7-456f-a11f-acc0179be0f7)

## XOR Operation
```
org 100h
mov [SI+2],ax;
mov ax,0A22h;
not ax
xor ax,bx; 
mov [0008h],ax;
ret
```
## Output
![image](https://github.com/user-attachments/assets/c197b9ac-7df9-4875-b517-0fbf75a5b668)


## Result :
Thus, Alp for fundamental arithmetic and logical operations are exected succesfully. 








