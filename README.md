# Ultrasonic Radar System using Arduino

This project demonstrates a *radar-like object detection system* using an *Arduino microcontroller* and an *HC-SR04 ultrasonic sensor*. The system measures distances in real-time and visualizes them on a laptop screen in a radar-style graphical interface.

## 🔹 Features
- Real-time object detection using *HC-SR04 ultrasonic sensor*  
- *Radar-style visualization* on PC (Processing IDE / MATLAB)  
- Displays distance and angle of detected objects  
- Compact and portable hardware design  
- Applications in *automation, robotics, and surveillance*  

## 🔹 Components Used
- Arduino Uno / Nano  
- HC-SR04 Ultrasonic Sensor  
- Servo Motor (for rotating the sensor)  
- Laptop with Processing IDE (for visualization)  
- Jumper Wires & Breadboard  

## 🔹 Circuit Diagram
- HC-SR04 connected to Arduino digital pins  
- Servo motor controlled by Arduino PWM pin  
- Arduino communicates with laptop via Serial (USB cable)  

## 🔹 Working
1. The ultrasonic sensor mounted on a servo rotates in a defined angle range (0°–180°).  
2. Distance data is collected at each angle and sent to the PC through serial communication.  
3. The Processing IDE reads the serial data and generates a *radar-like sweep visualization*.  
4. Detected objects appear on the radar interface at their respective distance and angle.  

## 🔹 Skills / Technologies
- Arduino Programming (C/C++)  
- Ultrasonic Sensor Interfacing  
- Serial Communication (Arduino ↔ PC)  
- Data Visualization using Processing IDE / MATLAB  
- Embedded Systems & Real-Time Applications  

## 🔹 How to Run
1. Upload the Arduino code (radar.ino) to your Arduino board.  
2. Open the radar_visualization.pde file in *Processing IDE*.  
3. Connect the Arduino to your laptop via USB and select the correct COM port.  
4. Run the Processing sketch to visualize the radar interface.  

## 🔹 Applications
- Obstacle detection in *robotics*  
- Real-time monitoring in *automation systems*  
- Low-cost *surveillance systems*  
- Educational demonstration of *ultrasonic sensing & visualization*  

## 🔹 Author
Developed by **[Siya Kashikar]**

