# HomeWork Week8
## PC
* code
```
CHIP PC {
    IN in[16],load,inc,reset;
    OUT out[16];

    PARTS:
    // Put your code here:
    Inc16(in=PC,out=I16);
    Mux16(a=PC,b=I16,sel=inc,out=iout);
    Mux16(a=iout,b=in,sel=load,out=lout);
    Mux16(a=lout,b=false,sel=reset,out=rout);
    Register(in=rout,load=true,out=PC,out=out);
}
```
* picture
![PICTURE](https://github.com/victor0520/co109a/blob/master/homework/IMG_20201230_230319.jpg)
