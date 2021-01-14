# Week9Homework
### Fill
* code
```
@8192               
D=A               
@0                
M=D                
@24576
D=M
@18                  
D;JNE            
//WHITE LOOP
@0
D=M               
M=M-1                
@0              
D;JEQ           
@16383          
A=D+A                
M=0              
@8                
0;JMP           
//BLACK LOOP
@0
D=M
M=M-1
@0
D;JEQ            
@24576
A=A-D
M=-1
@18
0;JMP  
```
* Assembler

![PICTURE](https://github.com/victor0520/co109a/blob/master/homework/fill1.JPG)
* CPUEmulator

![PICTURE](https://github.com/victor0520/co109a/blob/master/homework/fill2.JPG)
