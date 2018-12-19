# Ultrasonic-Distance-Sensor-HC-SR04-with-LCD-Display-and-Arduino

### Connection Guidelines:
1. HC-SR04 sensor attach to the Breadboard
2. HC-SR04 Sensor VCC connect to the Arduino Board +5V
3. HC-SR04 Sensor GND connect to the Arduino Board GND
4. HC-SR04 Sensor Trig connect to the Arduino Board Digital I/O 9
5. HC-SR04 Sensor Echo connect to the Arduino Board Digital I/O 10

### LCD Display Connection:

6. LCD VSS pin to Arduino GND
7. LCD VDD pin to Arduino 5V
8. LCD VO pin to 10k Potentiometer center pin or connect to GND directly
9. LCD RS pin to digital pin 1
10. LCD RW pin to Arduino GND
11. LCD Enable pin to digital pin 2
12. LCD D4 pin to digital pin 4
13. LCD D5 pin to digital pin 5
14. LCD D6 pin to digital pin 6
15. LCD D7 pin to digital pin 7
16. The 10k Potentiometer’s other legs connect to +5V and GND(if you used Potentiometer)
17. For the backlight of the display, pin 15 (A+) and 16 (K-) of the LCD connect to +5V and GND

If you want, can be use a 220 ohm resistor to power the backlight of the display.(optional)

## Diagram
![Cat](https://github.com/imranshakil/Ultrasonic-Distance-Sensor-HC-SR04-with-LCD-Display-and-Arduino/blob/master/diagram.jpg)

###### Now upload code in your arduino board
