# LED-bulb-and-Arduino-code
 LED bulb on the Arduino with a code and a button
 
 int ledPin = 2; // choose the pin for the LED
int inPin = 4;
/1 choose the input pin (for a pushbutton)
int val = 0;
/1 variable for reading the pin status
void setup {
pinMode(ledPin, OUTPUT); // declare LED as output
pinMode(inPin, INPUT);
// declare pushbutton as input
void 100p0)f
val = digitalRead(inPin); // read input value
if (val == HIGH) {
/1 check if the input is HIGH (button releaser
digitalWrite(ledPin, HIGH); // turn LED ON
} else {
digitalWrite(ledPin, LOW); // turn LED OFF
