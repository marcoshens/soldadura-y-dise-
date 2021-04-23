# soldadura 

He aprendido a soldar y la verdad que no era tan dificil como pensaba tienes que concertrarte y tener cuidado de no quemarte.

![](https://github.com/marcoshens/soldadura-y-dise-/blob/main/arduino.jpeg)

![](https://github.com/marcoshens/soldadura-y-dise-/blob/main/pizarra.jpeg)

el codigo que he puesto es este:

``` C++
const int LED=13;
const int BOTON=7;
int val;
void setup(){
pinMode(LED,OUTPUT);
pinMode(BOTON,INPUT);
}
void loop(){
val=digitalRead(BOTON);
if  (val==HIGH){
digitalWrite(LED,HIGH);
}
else { digitalWrite(LED,LOW);
}
}
```

![imagen](https://user-images.githubusercontent.com/78345826/115833708-a6393400-a414-11eb-8bdc-5d70d5b9f148.png)
