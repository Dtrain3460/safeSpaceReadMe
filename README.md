# Safe Space Software ReadMe Information

## Required materials
* Arduino Nano 33 BLE
* USB Type B Micro
* Arduino IDE Software
* Knowledge of C++ Coding

### Setting up the Arduino Software
1. Download the IDE from Arduino's official website: [![Web Site](https://www.arduino.cc/en/software)]
2. Once the software is downloaded, open up the application. Once the application is loaded, a sketch will automatically open up.
3. Go to Tools -> Manage Libraries, and type BLE in the search bar.
    * Download the ArduinoBLE library and confirm that the version of the library is 1.2.0.
4. Go to Tools -> Board: -> Boards Manager, and type BLE in the search bar.
    * Download Arduino Mbed OS Nano Boards, ensure the version is 2.0.
5. Go to Tools -> Board: -> Arduino Mbed OS Nano Boards -> Arduino Nano 33 BLE
6. Load in a Safe Space sketch onto the IDE.
7. Plug in the Arduino hardware with the USB corresponding to the sketch loaded into the software.
8. Go to Tools -> Port -> Select the COM in which the Arduino Nano 33 BLE is being sensed.
9. Upload the sketch to the Arduino.
10. Go to Tools -> Serial Monitor -> Choose the COM in which the arduino is plugged in.
    * You will be able to see what the Arduino is printing out. 
11. If the user would like to use the battery to power the Arduino. Plug in the battery, and disconnect the USB.
12. Model should be working with software inside internal memory.
