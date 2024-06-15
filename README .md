
# Smart Dustbin Project using Arduino

This project demonstrates a smart dustbin system using Arduino, where the dustbin lid opens automatically when someone approaches it, and closes after the trash is deposited. It uses an ultrasonic sensor to detect motion and an Arduino board to control the servo motor that operates the lid.


## Components Used:
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90)
- Jumper Wires
- Breadboard
- 5V Power Supply




## Circuit Diagram:

![Screenshot (234)](https://github.com/deva2025/Smart-Dustbin/assets/166497101/e5a269f1-f3a1-472b-b738-8dfe7fcc3343)

## Installation

1.Arduino IDE Setup:

- Download and install the Arduino IDE from arduino.cc.
- Connect your Arduino board to your computer using a USB cable.
  
2.Libraries:

- Install the required libraries:
- 'Servo' library for controlling the servo motor.
- 'NewPing' library for interfacing with the ultrasonic sensor.
  
3.Connections:

- Connect the ultrasonic sensor and servo motor to the Arduino board as per the circuit diagram.
  
4.Upload Code:

- Open 'Smart Dustbin arduino code' file in Arduino IDE.
- Verify and upload the code to your Arduino board.
  
  ![Screenshot (229)](https://github.com/deva2025/Smart-Dustbin/assets/166497101/d7675c40-4414-4d50-98a5-f0de4d069866)

  
  ![Screenshot (230)](https://github.com/deva2025/Smart-Dustbin/assets/166497101/edabb1c7-0124-477c-82f2-a4a644ae9156)
    
## Features

- Automatic Lid Operation: Opens upon approach detected by ultrasonic sensor.
- Hands-Free Operation: Allows touchless trash disposal for hygiene.
- Auto-Closing Mechanism: Lid closes automatically after use.
- Adjustable Sensitivity: Customizable sensor range for various distances.
- Low Power Consumption: Efficient for prolonged battery use.
- Compact and Modular Design: Arduino-based, adaptable to different setups.
- User-Friendly Interface: Simple controls with clear feedback for ease of use.







## Usage
 - Power up your Arduino board using a suitable power supply.
- The ultrasonic sensor detects nearby motion.
- As someone approaches the dustbin, the servo motor opens the lid automatically.
- Dispose of trash into the dustbin.
- After a few seconds, the lid closes automatically.

