# EXPERIMENT--01-ALP-FOR-8086
Name : Nithila S
Reg No: 212224040224





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

mov ax,10abh
mov bx,20cdh
add ax,bx

ret
```



## Output  
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/a06643ef-d213-4012-9be6-c77d3ec27d4a" />

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h

mov ax,10abh
mov bx,20cdh
sub ax,[bx]

ret
```
 
## Output  
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/e131fd0f-319f-4763-8c4f-95278ea6dcbf" />

## Multiplication alp 
```
org 100h

mov ax,023ah
mov bx,02a1h
mul bx

ret
```
 ## Output  
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/2fbb46fd-d4be-411e-a057-0c94cc856644" />


## Division alp 
```
org 100h

mov ax,023ah
mov bx,02a1h
div bx

ret
```

## Output  
<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/07e86287-4db9-438d-a32d-c55df2ba808c" />

## AND alp
```
org 100h

mov ax,15cah
mov bx,18edh
and ax,bx

ret
```
## Output
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/b620845b-62c6-446a-9d00-21f5ff5f329c" />

## Or alp
```
org 100h

mov ax,15cah
mov bx,18edh
or ax,[bx]

ret
```
## Output
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/59d1093d-d869-4a4c-8289-8ce68de841ed" />

## Not alp
```
org 100h

mov ax,023ah
not bx

ret

```
## Output
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/f966089f-1587-44c2-9e02-e031f6375bf6" />

## Xor alp
```
org 100h

mov ax,023ah
mov bx,02a1h
xor ax,bx

ret
```

## Output
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/eb32b154-294a-4e47-a8bd-bf26b617da87" />



## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








