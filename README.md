# MINI TASK - 1

## 1. KEYBOARD USING SMD SENSORS:

Link: https://www.instructables.com/id/Velocity-Sensitive-Cardboard-Keyboard/

In this project, a small keyboard is made using cardboard. The cardboard is cut into various small pieces which corresponds to various keys in the keyboard. The various pieces are joined using hot silicone. There are 5 keys which correspond to C,D,E,F,G frequencies and is fitted into a larger cardboard using rubber straps, and there are slots made for inserting them onto the base. SMD sensors are used to detect which key is being pressed, and is therefore fitted below each key of the keyboard. The sensors are connected to 5 analog pins of an Ardunio Mega and is coded using the toneAC library such that sound of the corresponding frequency comes when that particular key is pressed. In this way, this project was implemented.

## 2. AUTOMATIC WATER LEVEL CONTROLLER:

Link: https://www.electronicshub.org/water-level-controller-using-8051-microcontroller/

In this project, the level of the water is automatically controlled using the 8051 microcontroller which is programmed using the Keil uVision IDE. The aim of this project is to control the water in the tank such that the motor stops running automatically when the tank is full and it starts running when the tank is empty. This reduces human intervention as well as water losses due to water overflowing from the tank. This is based on the principle that water conducts electricity. Wires are connected to different levels of water - either LOW, MEDIUM, HIGH or QUARTER full, HALF full,... There is an LCD display as well which denotes the level of water present in the tank, just in case if someone wants to know the level of water. If initially the tank is empty, the motor starts running, and when the water at appropriate levels are reached, the LCD displays the appropriate level of water. When the tank is full, the motor is automatically switched off. When the water tank is on the EMPTY level, the motor gets turned on automatically, to refill the water in the tank. The display on the LED and the motor is controlled by the 8051 microcontroller.

## 3. BIDIRECTIONAL VISITOR COUNTER:

Link: https://www.electronicshub.org/bidirectional-visitor-counter-using-8051-microcontroller/

The aim of this project is to display the number of visitors who are currently present in a room by sensing the entry and exit of people at the entrance. It is displayed on an LCD display which is controlled by an 8051 microcontroller. There are two IR sensors which are controlled by the microcontroller and they sense movement of people entering or exiting the room. How the sensors do this can be easily explained. Let us call the sensors, sensor 1 and sensor 2 such that sensor 2 is inside the room and sensor 1 is near the entrance. When there is some movement sensed by sensor 1 and then at sensor 2, it means that the person has entered the room and the count in the LCD goes up by 1. Rather, if there is some movement sensed by sensor 2 and then at sensor 1, then the person has left the room and hence the count in the LCD decreases by 1.

## 4. REAL TIME CLOCK (RTC) USING ARDUINO:

Link: https://www.electronicshub.org/arduino-real-time-clock-tutorial/

This project implements a real time clock (RTC) by interfacing an RTC IC onto an Arduino. Here, the RTC IC used is DS1307, which has some really cool features. It has information about the complete date and time (i.e.) hours, minutes, seconds, year, month, date and day of the week. It consumes really really low power as it draws only 500nA when connected to a battery. It is connected to an Arduino and the Arduino is connected to an LCD display, which displays the complete date and time. This is done by using the libraries LiquidCrystal.h (for writing onto the LED) and RTClib.h (for getting information from the RTC IC).

## 5. RGB LED MATRIX:

Link: https://www.electronicshub.org/diy-rgb-led-matrix/

This project aims to create an RGB LED matrix which is to be controlled by a mobile app designed specifically for this purpose. This LED matrix consists of 8 rows and 6 columns. Each row contains red, green and blue LEDs which are cut from an LED strip. Each set of R,G and B LEDs are cut and pasted on a panel. Holes are drilled through the metal contacts in order to make connections. Further, an IC 74HC595N is used, which is actually an 8-bit serial-in, serial or parallel-out shift register, which gets serial input from the Arduino and converts it to parallel output which can be fed to the LEDs. Transistors are used, one for each colour of LEDs to drive them. The circuit is then done on a PCB. Entire control of the LED matrix is done by the app (MIT App inventor 2).
