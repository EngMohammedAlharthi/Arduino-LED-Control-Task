const int button1 = 2;
const int button2 = 3;
const int button3 = 4;

const int led1 = 12;
const int led2 = 11;
const int led3 = LED_BUILTIN; 

void setup() {

  pinMode(button1, INPUT);
  pinMode(button2, INPUT);
  pinMode(button3, INPUT);

  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
}

void loop() {
  
  int b1 = digitalRead(button1);
  int b2 = digitalRead(button2);
  int b3 = digitalRead(button3);

  
  digitalWrite(led1, b1);
  digitalWrite(led2, b2);
  digitalWrite(led3, b3);
}
