# EMBEDDED-SYSTEM-LAB1// สัญญาณขอความช่วยเหลือ sos คำว่า (191)แจ้ง ตร.
void setup() {
  // put your setup code here, to run once:
pinMode(13,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(13,HIGH);//1 .
delay(400);
digitalWrite(13,LOW);//1 .
delay(400);
digitalWrite(13,HIGH);//1 - 1
delay(2000);
digitalWrite(13,LOW);//1 - 1
delay(2000);
digitalWrite(13,HIGH);//1 - 2
delay(2000);
digitalWrite(13,LOW);//1 - 2
delay(2000);
digitalWrite(13,HIGH);//1 - 3
delay(2000);
digitalWrite(13,LOW);//1 - 3
delay(2000);
digitalWrite(13,HIGH);//1 - 4
delay(2000);
digitalWrite(13,LOW);//1 - 4
delay(2000);

digitalWrite(13,HIGH);
delay(200);
digitalWrite(13,LOW);
delay(200);

digitalWrite(13,HIGH);//9 - 1
delay(2000);
digitalWrite(13,LOW);//9 - 1
delay(2000);
digitalWrite(13,HIGH);//9 - 2
delay(2000);
digitalWrite(13,LOW);//9 - 2
delay(2000);
digitalWrite(13,HIGH);//9 - 3
delay(2000);
digitalWrite(13,LOW);//9 - 3
delay(2000);
digitalWrite(13,HIGH);//9 - 4
delay(2000);
digitalWrite(13,LOW);//9 - 4
delay(2000);
digitalWrite(13,HIGH);//9 . 
delay(400);
digitalWrite(13,LOW);//9 .
delay(400);

digitalWrite(13,HIGH);
delay(200);
digitalWrite(13,LOW);
delay(200);

digitalWrite(13,HIGH);//1 . 
delay(400);
digitalWrite(13,LOW);//1 .
delay(400);
digitalWrite(13,HIGH);//1 - 1
delay(2000);
digitalWrite(13,LOW);//1 - 1
delay(2000);
digitalWrite(13,HIGH);//1 - 2
delay(2000);
digitalWrite(13,LOW);//1 - 2
delay(2000);
digitalWrite(13,HIGH);//1 - 3
delay(2000);
digitalWrite(13,LOW);//1 - 3
delay(2000);
digitalWrite(13,HIGH);//1 - 4 
delay(2000);
digitalWrite(13,LOW);//1 - 4
delay(2000);
}
