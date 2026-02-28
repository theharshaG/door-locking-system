# door-locking-system

# Password Based Door Lock System (ESP32)

## Project Overview
This project demonstrates a **password-protected door lock system**
using an **ESP32 and a Servo motor**.

The user enters a password through the **Serial Monitor**.
- Correct password → Door opens
- Wrong password → Door remains closed
  
## Components Required
- ESP32
- Servo Motor (SG90 / MG90)
- Jumper Wires
- USB Cable
 
## Connections
Servo Wire-->ESP32 Pin |

Red ---->5V(power supply)
Brown/Black ---->GND 
Yellow/Orange--->GPIO 18

Use external 5V supply for servo if needed.

## Concepts Used
- Serial Communication
- Servo Motor Control
- Conditional Statements
- String Handling

##  How to Run
1. Install **ESP32Servo Library**
2. Connect servo motor properly
3. Upload code to ESP32
4. Open Serial Monitor (115200 baud)
5. Enter password → `1234`

## 📟 Sample Output
Enter the password:
1234
Access Granted - Door Opened.

## Learning Outcome
- Learn servo motor control using ESP32
- Understand password-based access systems
- Practice serial input handling

## Author
Harsha G
