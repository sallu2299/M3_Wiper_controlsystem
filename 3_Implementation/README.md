#include<reg52.h>
Static int y;
sbit x=p3^3;
Void zcr(void);
Void msecdelay2();
Void msecdelay5();
Void main(){
P1=0*off;
P2=0*00;
X=1;
While(1){
If(p1==0*ofe){
y=0;
While(p1==0*of5){
If(y==0){
Zcr(); 
Msecdelay2(); 
P2=0*of;
Msecdelay5(); 
P2=0*00;
y++; 
}
If(y==1){
Zcr(); /
Msecdelay2(); 
P2=0*of;
Msecdelay5(); 
P2=0*00;
y++; 
If (y==2){
P2=0*fo;
Msecdelay5(); 
P2=0*00;
y++; 
}
If (y==3){
Zcr(); 
Msecdelay2(); 
Msecdelay5(); 
P2=0*00;
Y=0;
}
}
}
else if(p1=0*fc) {
y=0;
While(p1==0*fa){
If(y==0){
Zcr(); 
Msecdelay2();
P2=0*of;
Msecdelay5(); 
P2=0*00;
y++; 
}
If(y==1){
Msecdelay2(); 
P2=0*of;
Msecdelay5(); 
P2=0*00;
y++; 
}
If(y==2) {
Zcr(); 
Msecdelay2(); 
P2=0*of;
Msecdelay5(); 
P2=0*00;
y++;
}
If(y==3){
Zcr(); 
Msecdelay2(); 
P2=0*fo;
Msecdelay5(); 
P2=0*00;
y++; 
}
If(y==4){
Zcr(); 
P2=0*fo;
Msecdelay5(); 
P2=0*00;
y++; 
}
If(y==5){
Zcr(); 
P2=0*fo;
Msecdelay5(); 
P2=0*00;
Y=0;
}
}
}
else{
If(y==0){
Zcr(); 
Msecdelay2(); 
P2=0*fo;
Msecdelay5(); 
P2=0*00;
y++; 
}
If(y==1)
{
Zcr(); 
Msecdelay2(); 
P2=0*fo;
Msecdelay5(); 
P2=0*00;
y=0;
}
}
}
}
Void zcr(void) {
While(x=1);
While(x=0);
}
Void msecdelay2(){
Unsigned int I,j;
For(i=0;i<1,i++){
For(j=0;j<50,i++){;}
}
}
Void msecdelay5(){
Unsigned int m,n;
For(m=0;m<5,m++){
For(n=0;n<100,n++)
}
}
