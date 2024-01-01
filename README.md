# IOT-Project-2
# Machine Learning Based Wirless Home Automation

This project demonstrates a wireless communication system using two Xiao BLE ESP32-C3 boards. The transmitter board is equipped with an MPU6050 accelerometer, while the receiver board features a 0.96" OLED display. The system is designed to detect movements using the MPU6050 and display corresponding signals on the OLED display and turn on and off the lights.

## Hardware Components

- **Transmitter Board:**
  - Xiao BLE ESP32-C3
  - MPU6050 Accelerometer

- **Receiver Board:**
  - Xiao BLE ESP32-C3
  - 0.96" OLED Display

## Dependencies

- [Edge Impulse](https://www.edgeimpulse.com/): Used for training the MPU6050 data.

- ![image](https://github.com/aliabidlodhi74/IOT-Project-2/assets/83972129/6b46aa26-4a01-46ad-8d11-eeb2181d55a4)


## Getting Started

1. **Clone the Repository:**
   
https://github.com/aliabidlodhi74/IOT-Project-2

2. **Hardware Setup:**
   
   - **Connect transmitter esp32 board with mpu6050**
     ![image](https://github.com/aliabidlodhi74/IOT-Project-2/assets/83972129/08c7ec3c-fb3e-4739-b31b-32b653e0d787)


   - **Connect Receiver esp32 board with OLED**
   
     ![image](https://github.com/aliabidlodhi74/IOT-Project-2/assets/83972129/251678a5-dd16-4be0-9a75-de70e1ba2914)


3. **Edge Impulse Setup:**

   - Create Account at edge impulse
   - To run edge impulse follow the installation tutorial on the following link
     https://docs.edgeimpulse.com/docs/tools/edge-impulse-cli/cli-installation
   - Upload dataForwarder.ino firmware in the transmitter board with mpu6050 connected
   - Open CMD and run this command
     
      **edge-impulse-data-forwarder**

     
   - Provide name of 3 axis as aX, aY, aZ and name of the device as shown in the picture below
     
   ![image](https://github.com/aliabidlodhi74/IOT-Project-2/assets/83972129/41be1e86-7e96-4310-a0d6-1b9805dc751b)


    - 
