# zadanie-z-programowania-c-
dzien 2 zadanie 6
Wypisz sinusy i cosinusy kątów 0...180 stopni z krokiem co 30 stopni za pomocą pętli for.

#include<stdio.h></n>

#include<math.h>
int main(){
int x; 
for(x=0;x<=180;x=x+30){
printf("sin(%3d)=%7.4lf  ", x,sin(x*M_PI/180));
printf("cos(%3d)=%7.4lf\n", x,cos(x*M_PI/180));
}
return 0;
}
