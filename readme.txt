/*
 RobotGeek Floormat Demo
 
 This example demonstrates the use of pinMode(INPUT_PULLUP) to read from
 a floormat switch. The code reads digital input on pin 2 and turns
 Digital Pin 4 HIGH when pin 2 goes LOW.
 
 The circuit: 
 Digital pin 2 -  Floomat switch
 Digital pin 4 - LED / Buzzer / Relay / Powertail Switch
 
 Since a raw switch like a floormat leaves the digital pin open we need to make
 use of an internal 20K-ohm resistor to pull up to 5V. This configuration causes
 the input to read HIGH when the switch is open, and LOW when it is closed. 
 
 Products Used in this demo
 - http://www.robotgeek.com/store/Search.aspx?SearchTerms=floor%20mat
 - http://www.robotgeek.com/robotgeek-geekduino-sensor-kit
 - http://www.robotgeek.com/robotgeek-led-driver
 - http://www.robotgeek.com/robotgeek-buzzer
 - http://www.robotgeek.com/store/p/6437-PowerSwitch-Tail-II.aspx
 - http://www.robotgeek.com/robotgeek-relay
 - http://www.robotgeek.com/robotgeek-small-workbench.aspx
 - http://www.robotgeek.com/p/power-supply-6vdc-2a.aspx

 */
