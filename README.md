# EXPERIMENT 01 ALP FOR 8086
```
Name :Nikhil M
Roll no : 212222230095
Date of experiment : 21/08/2025
```




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


## Addition of 16 bit ALP 
```
MOV AX,48c6H
MOV BX,24e8H
ADD AX,BX
RET
```


## Output  
<img width="934" height="558" alt="image" src="https://github.com/user-attachments/assets/78a3a907-e009-4c49-8935-f9167e02af4e" />

## Subtraction of 16 bit numbers  ALP 
 ```
MOV AX,89a7H
MOV BX,18f2H
SUB AX,BX
RET
```
## Output  
<img width="935" height="555" alt="image" src="https://github.com/user-attachments/assets/548456e8-36a4-4c37-bb58-8e425def5188" />

## Multiplication of 16 bit numbers ALP 
```
org 100h
MOV AX,6d42H
MOV BX,387bH
MUL BX
RET
```
 ## Output  
<img width="1320" height="783" alt="image" src="https://github.com/user-attachments/assets/45fdc9c7-7d61-46f2-b33f-594118d82883" />



## Division of 16 bit numbers ALP
```
MOV AX,5241H
MOV BX,27a1H
DIV BX
RET
```

## Output  
<img width="1320" height="785" alt="image" src="https://github.com/user-attachments/assets/781841ae-584c-47b6-9b21-e9a9b7b3ed80" />


# AND of 16 bit numbers ALP
```
MOV AX,241fH
MOV BX,4372H
AND AX,BX
RET
```
# Output
<img width="1331" height="801" alt="image" src="https://github.com/user-attachments/assets/7ea84a8d-f9b5-4529-8bce-99b74b4a69b6" />


# OR of 16 bit numbers ALP
```
MOV AX,45d1H
MOV BX,662aH
OR AX,BX
RET
```
# Output
<img width="1339" height="801" alt="image" src="https://github.com/user-attachments/assets/9947640d-0b0d-427c-b9b1-0e43e0f48386" />


# NOT of 16 bit numbers ALP
```
MOV AX,561cH
NOT AX
RET
```

# Output
<img width="1335" height="794" alt="image" src="https://github.com/user-attachments/assets/60a53bee-fbb3-4a94-8c0a-835beda34383" />

# XOR of 16 bit numbers ALP
```
MOV AX,98b2H
MOV BX,44d2H
XOR AX,BX
RET
```

# Output
<img width="1339" height="791" alt="image" src="https://github.com/user-attachments/assets/fb1a2055-48a7-4768-8ecc-bbbe89368895" />



## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








