# EXPERIMENT--01-ALP-FOR-8086
## Name : Shree Lekha.S
## Roll no.:212223110052
## Date of experiment :


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







## Programs for arithmetic  operations:

## Addition  of 8 bit ALP:
```
MOV Al,28H
MOV Bl,19H
ADD Al,Bl
RET
```
## Output  

![Screenshot 2025-05-20 112500](https://github.com/user-attachments/assets/f73e2f0f-c67c-4989-a610-45cc809ad15b)

 
## Subtraction   of 8 bit numbers  ALP:
```
MOV Al,28H
MOV Bl,19H
SUB Al,Bl
RET
```
## Output  
![Screenshot 2025-05-20 112733](https://github.com/user-attachments/assets/b4d368fa-bfa7-4811-af12-584793d29a4b)


## Multiplication of 8 bit number ALP:
```
MOV Al,28H
MOV Bl,19H
MUL Bl
RET

```
 ## Output  
![Screenshot 2025-05-20 112543](https://github.com/user-attachments/assets/a3ce16d0-7635-4093-9836-ed1414766a92)


## Division of 8 bit number ALP:
```
MOV Al,28H
MOV Bl,19H
DIV Bl
RET
```
## Output  

![Screenshot 2025-05-20 112623](https://github.com/user-attachments/assets/14f0b017-7c81-44d1-9458-3c8a450425ba)

## AND of 8 bit number ALP:
```
MOV Al,28H
MOV Bl,19H
AND Al,Bl
RET
```
## Output  

![Screenshot 2025-05-20 113217](https://github.com/user-attachments/assets/ba5823d0-f090-4fa4-bb8f-214f25e2949c)

## OR of 8 bit number ALP:
```
MOV Al,28H
MOV Bl,19H
OR Al,Bl
RET
```

## Output 
![Screenshot 2025-05-20 113115](https://github.com/user-attachments/assets/5ac05155-c7db-496a-91d9-b204fab97e31)

## XOR of 8 bit number ALP:
```
MOV Al,28H
MOV Bl,19H
XOR Al,Bl
RET
```
## Output:

![Screenshot 2025-05-20 113028](https://github.com/user-attachments/assets/531e7b5c-1a40-47a4-a5da-8c6c1b725788)


## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.






