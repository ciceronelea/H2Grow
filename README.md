README

-Created using C++

1.)The compiler to be used is (Arduino IDE, Microsoft Visual Studio, Sublime)
2.) For great library support and arduino interfacing use Arduino IDE 

// Code generated for basic Arduino UNO interaction to board NODEMCU ESP-8266 V3
// H2 Grow

#include <SoftwareSerial.h>

SoftwareSerial esp8266(2, 3): // RX, TX pins on Arduino uno

 void setup() {
 Serial.begin(9600); // Please select 9600 Baud rate for the serial monitor in arduino uno to prevent code Malfunction
 esp8266.begin(9600);

 }

  void loop() {
  // Send AT command to check if nodemcu is responding

  delay(500);

  //check if there is any response from ESP8266
delay ("Please Specify time") // specify the time in Millisecond eg. 1000 Millisecond == 1 Second 

Gitpush /= 

// Github Repository created to collab code and to help code flow

 

