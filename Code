// code to input for the Application
int led1=8;
int led2=9;
int led3=10;
char val;

void setup()
{
  pinMode(led1,OUTPUT);
  pinMode(led2,OUTPUT);
  pinMode(led3,OUTPUT);
  Serial.begin(9600);
}
void loop()
{
  val=Serial.read();
  Serial.println(val);
 
 if(val=='1')
{
  digitalWrite(led1,HIGH);
}
else if(val=='2')
{
  digitalWrite(led2,LOW);
}
else if(val=='3')
{
  digitalWrite(led3,HIGH);
}
else if(val=='4')
{
  digitalWrite(led1,LOW);
}
else if(val=='5')
{
  digitalWrite(led2,HIGH);
}
else if(val=='6')
{
  digitalWrite(led3,LOW);
}

}
