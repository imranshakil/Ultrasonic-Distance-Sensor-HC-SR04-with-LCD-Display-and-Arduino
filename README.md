# Ultrasonic-Distance-Sensor-HC-SR04-with-LCD-Display-and-Arduino

###Connections Guidelines:
HC-SR04 sensor attach to the Breadboard
HC-SR04 Sensor VCC connect to the Arduino Board +5V
HC-SR04 Sensor GND connect to the Arduino Board GND
HC-SR04 Sensor Trig connect to the Arduino Board Digital I/O 9
HC-SR04 Sensor Echo connect to the Arduino Board Digital I/O 10

###LCD Display Connection:
LCD VSS pin to Arduino GND
LCD VDD pin to Arduino 5V
LCD VO pin to 10k Potentiometer center pin or connect to GND directly
LCD RS pin to digital pin 1
LCD RW pin to Arduino GND
LCD Enable pin to digital pin 2
LCD D4 pin to digital pin 4
LCD D5 pin to digital pin 5
LCD D6 pin to digital pin 6
LCD D7 pin to digital pin 7
The 10k Potentiometer’s other legs connect to +5V and GND(if you used Potentiometer)
For the backlight of the display, pin 15 (A+) and 16 (K-) of the LCD connect to +5V and GND

If you want, can be use a 220 ohm resistor to power the backlight of the display.(optional)

######Then upload code in your arduino board
