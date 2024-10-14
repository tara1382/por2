پروژه روشن شدن چراغ ها برخلاف هم
int led = 9;
int led2 = 13;
void setup() {
  // put your setup code here, to run once:
pinMode(led,OUTPUT);
pinMode(led2,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(led,HIGH);
delay(1000);
digitalWrite(led,LOW);
delay(1000);
digitalWrite(led2,HIGH);
delay(1000);
digitalWrite(led2,LOW);
delay(1000);
}
با کمک این کد زمانی که led شماره 1 روشن است led شماره 2 خاموش میشود و در زمانی که led شماره 2 روشن است led شماره 1 خاموش میشود.
"E:\ریزپردازنده\IMG_3547.HEIC"
