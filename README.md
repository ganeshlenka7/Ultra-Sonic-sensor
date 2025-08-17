Ultrasonic Distance Measurement with LED Indicator

This project demonstrates the use of an HC-SR04 ultrasonic sensor with an Arduino to measure distance and control an LED based on proximity. It provides a simple example of sensor interfacing, distance calculation, and digital output control using Arduino.

Components

Arduino Uno

HC-SR04 Ultrasonic Sensor

LED

Resistor (220Ω recommended)

Jumper wires

Breadboard

Features

Measures distance in centimeters using ultrasonic waves.

Displays distance readings on the Serial Monitor.

Activates an LED when an object is detected within a specific range (≤ 30 cm).

How It Works

The trigger pin of the ultrasonic sensor sends out a short ultrasonic pulse.

The echo pin receives the reflected pulse.

The Arduino calculates the distance based on the duration of the echo pulse.

If the measured distance is less than or equal to 30 cm, the LED turns on; otherwise, it remains off.

Wiring diagram

Trig Pin → Arduino Pin 9

Echo Pin → Arduino Pin 10

LED → Arduino Pin 13 (with resistor)

VCC & GND → Arduino 5V & GND


![Ultra sonic circuit diagram](Ultra%20Sonic%20Sensor)
Code

The Arduino sketch handles the pulse generation, distance calculation, and LED control using simple digitalWrite, pinMode, and pulseIn functions.

youtube channel video link :
