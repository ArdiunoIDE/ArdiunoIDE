int led=6;

void setup() {

pinMode(led,OUTPUT);  
}
void loop() {
analogWrite (led,255)

delay(500);


analogWrite (led,200)

delay(500);

analogWrite (led,100)

delay(500);

analogWrite (led,99);
 
 delay(500);
   
analogWrite (led,78);
 
 delay(500);

analogWrite (led,50);
 delay(500);
 
analogWrite (led,0      );
 delay(500);

}
