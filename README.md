# Sonar Ultrasonic Sensor with Arduino

This project demonstrates the use of an ultrasonic sensor with an Arduino Uno to measure distance and angle. A servo motor is used to rotate the sensor, allowing for a wider scanning range.

## Components Used
- **Arduino Uno**: Microcontroller to read sensor data and control the servo motor.
- **HC-SR04 Ultrasonic Sensor**: Measures distance by sending and receiving ultrasonic waves.
- **Servo Motor**: Rotates the ultrasonic sensor to scan different angles.

## Functionality
- The ultrasonic sensor emits a sound pulse and calculates the time taken for the echo to return. 
- The distance is calculated based on the speed of sound.
- The servo motor allows the sensor to sweep through a range of angles, providing a comprehensive distance reading across a wider area.
- Results are displayed in a separate Processing application, showing distance and angle in real time.
