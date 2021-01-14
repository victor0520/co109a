# Week8Homework
### mult
* code
```
@0
D=A //先將D設0
@2  
M=D //將結果先規0
@0  //LOOP1
D=M //將R0設為計數器
@16
D;JEQ //D等於0跳出迴圈
@1
D=M  //將值輸入D
@2
M=D+M //將D值加入R2
@0
M=M-1 //計數器-1
@4  
0;JMP //回到LOOP1
@16
0;JMP
```
* Assembler
![PICTURE](https://github.com/victor0520/co109a/blob/master/homework/.JPG)
* CPUEmulator
![PICTURE](https://github.com/victor0520/co109a/blob/master/homework/1.JPG)
