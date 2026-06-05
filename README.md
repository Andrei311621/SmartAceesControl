# SmartAceesControl




📌 Overview

Smart Access Control System is an IoT-based project that combines electronics, embedded programming, cloud services, and mobile application development to create a complete access control solution.

The system collects data from sensors, processes it through embedded hardware, communicates with a Firebase cloud database, and allows monitoring and control through an Android application developed using MIT App Inventor.

🧩 System Architecture <br>

         Sensors → Arduino → ESP Module → Firebase → Android Application

The system consists of four main components:

🔌 Hardware Layer<br>
💻 Embedded Software Layer<br>
☁️ Firebase Cloud Database<br>
📱 Android Mobile Application







          🔌 Hardware

The hardware section contains the electronic components used to build the system, including:

Sensors
Arduino board
ESP module
Buzzer (alarm system)
Power supply components
Supporting electronic circuitry

The complete circuit schematic and hardware documentation can be found in the hardware folder.

         💻 Embedded Software

The embedded software is responsible for:

Reading sensor data
Processing access control events
Triggering the alarm system
Communicating with Firebase through the ESP module
Managing the overall system logic

The source code is available in the software folder.

        ☁️ Firebase Integration

Firebase is used as the cloud communication layer between the embedded system and the Android application.

Main functionalities:

Real-time data storage
Remote system monitoring
Alarm state management
Synchronization between devices

The Firebase configuration and database structure can be found in the firebase folder.

        📱 Android Application

The Android application was developed using MIT App Inventor.

Application Features
Administrative access interface
Alarm control functionality
Real-time communication with Firebase
User-friendly graphical interface
Application Structure

The application was created using the two main MIT App Inventor environments:

-Designer:

Used to create and customize the user interface through drag-and-drop components.

-Blocks:

Used to implement the application logic through visual programming blocks.

🚀 Features<br>
IoT-based access control system<br>
Real-time Firebase integration<br>
Android mobile application<br>
Alarm management functionality<br>
Wireless communication<br>
Modular system architecture<br>
Cloud-based monitoring<br>

🛠️ Technologies Used
Arduino<br>
ESP Module<br>
Embedded C/C++<br>
Firebase Realtime Database<br>
MIT App Inventor<br>
Electronics and Sensors<br>
Git<br>
GitHub<br>

🎓 What I Learned

Through this project, I gained practical experience in:

Embedded systems development<br>
Electronics design and integration<br>
IoT architecture<br>
Cloud database integration<br>
Mobile application development<br>
Wireless communication<br>
System debugging and testing<br>
End-to-end system design<br>

