#define come1 3
 #define come2 4
 #define turn1 6
 #define turn2 7
 #define En1 2 // L293D enable pin pour le premier moteur //Pin de controleur qui  active mouteur 1
#define En2 5 
int Mspeed = 500;
void setup() {
   pinMode(come1, OUTPUT);
   pinMode(come2, OUTPUT);
   pinMode(turn1, OUTPUT);
   pinMode(turn2, OUTPUT);
   pinMode(En1, OUTPUT);
   pinMode(En2, OUTPUT);

    }
   void loop(){
     analogWrite(En1, Mspeed);
               digitalWrite(come2, HIGH);
                digitalWrite(come1, LOW);
                delay(3000);
                 analogWrite(En2, Mspeed);
               digitalWrite(turn2, HIGH);
                digitalWrite(turn1, LOW);
                delay(4000);
                digitalWrite(turn2, LOW);
                digitalWrite(turn1, HIGH);
                delay(500);
                 digitalWrite(turn2, LOW);
                digitalWrite(turn1, LOW);
                  digitalWrite(come1, HIGH);
                digitalWrite(come2, LOW);
                
                }
