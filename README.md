
# EXPERIMENT--01-ALP-FOR-8086
Name : GUNTUR SHAIK MOHAMMAD SHAHIL

Roll no : 212223240044







## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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
mov ax,4554h;
mov bx,3322h;
add ax,bx
mov [6000h],ax;
ret
```


## Output  
![Screenshot 2024-08-19 133903](https://github.com/user-attachments/assets/0ede5431-9091-4a4a-922e-bd0c96881715)


 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h
mov ax,4050h;
mov bx,3078h;
sub ax,bx;
mov [6000h],ax;
ret
``` 
## Output  
![Screenshot 2024-08-19 134411](https://github.com/user-attachments/assets/693fa82e-048b-49a7-8709-715fddee9f73)


## Multiplication alp 
```
org 100h
mov ax,4050h;
mov bx,3078;
mul ax;
mov [6000h],ax;
ret
```
 ## Output 
![Screenshot 2024-08-19 135826](https://github.com/user-attachments/assets/b443c6fc-ef50-41bc-9acd-270e4e90cfc7)


## Division alp 
```
org 100h
mov ax,4050h;
mov bx,3078h;
div ax
mov [6000h],ax;
ret
```

## Output
![Screenshot 2024-08-19 135925](https://github.com/user-attachments/assets/bbcb25e5-d132-44f8-bef5-d3bc3dfde19a)

## Programs For Logical Operators:
## AND
```
org 100h
mov bx,1000h;
and bx,1111h;
mov [0040h+02],bx;
ret
```
## Output  
![Screenshot 2024-08-21 223009](https://github.com/user-attachments/assets/268bf0ca-fda0-49d2-9e9a-52dc59d8ba84)



## OR:
```
org 100h
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```
## Output
![Screenshot 2024-08-21 223354](https://github.com/user-attachments/assets/e00d9979-dce3-47c7-bcfc-33c428de096f)


## NOT:
```
org 100h
mov bx,0040h;
mov ax,[bx]; 
not al;
mov [0040h+04],ax;
ret
```
## Output
![Screenshot 2024-08-21 223530](https://github.com/user-attachments/assets/e445a119-7e2f-445a-a6b9-b9f84ee5468c)


## XOR:
```
org 100h
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
ret
```
## Output:
![Screenshot 2024-08-21 223624](https://github.com/user-attachments/assets/76f1dd3a-2892-47d0-b9ca-9237d88fadec)


## Result : 
Thus, to write and execute ALP on fundamental arithmetic operations and Logical operations is successful.
 
