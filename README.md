backpack
========
int x = 1000;
void setup(){
  pinMode(13,OUTPUT);
    pinMode(7,OUTPUT);
     pinMode(3,OUTPUT);
}
void loop(){
  digitalWrite(13,HIGH);
  delay(x);
  digitalWrite(7,HIGH);
  delay(x);
   digitalWrite(3,HIGH);
  delay(x);
  digitalWrite(13,LOW);
  delay(x);
   digitalWrite(7,LOW);
  delay(x);
   digitalWrite(3,LOW);
  delay(x);
 }
}
