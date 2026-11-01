# ESP32-Based RFID Smart Attendance System

## Project Overview

The RFID-Based Smart Attendance System is an IoT-based project developed using the ESP32 microcontroller to automate student attendance tracking.

The system uses RFID cards to identify students, displays their attendance status on an LCD screen, and automatically records attendance data in Google Sheets through Wi-Fi connectivity.

## Hardware Components

- ESP32 Development Board
- MFRC522 RFID Reader Module
- RFID Cards / Tags
- 16×2 I2C LCD Display
- Buzzer
- Connecting Wires
- Breadboard

## Technologies & Libraries Used

- **Arduino IDE** – Programming and microcontroller development.
- **ESP32** – Main microcontroller and Wi-Fi connectivity.
- **MFRC522 Library** – RFID card detection and UID identification.
- **SPI Communication** – Communication between ESP32 and RFID reader.
- **I2C Communication** – LCD interfacing.
- **Google Apps Script** – Connecting the ESP32 to Google Sheets.
- **HTTP Communication** – Sending attendance data over Wi-Fi.

## Working Principle

1. The student scans their RFID card using the MFRC522 reader.
2. The ESP32 reads the card's unique identification number (UID).
3. The UID is compared with the registered student database.
4. If the card is valid, the student's name and class are displayed on the LCD.
5. A buzzer provides audio feedback during scanning.
6. Attendance status is automatically sent to Google Sheets through Wi-Fi.
7. Invalid cards are identified and access is denied.

## Key Features

- Contactless RFID-based student identification.
- Automatic attendance marking.
- Real-time LCD feedback.
- Wi-Fi-based attendance data transmission.
- Google Sheets integration for attendance storage.
- Duplicate attendance prevention during a session.
- Serial Monitor-based attendance reporting.
- Invalid RFID card detection.

## System Architecture

**RFID Card → MFRC522 Reader → ESP32 → LCD Display / Buzzer**

**ESP32 → Wi-Fi → Google Apps Script → Google Sheets**

## Applications

- Educational institutions
- Smart classroom management
- Automated attendance monitoring
- IoT-based access and identification systems

## Learning Outcomes

- ESP32 microcontroller programming.
- RFID interfacing and UID identification.
- SPI and I2C communication protocols.
- IoT and Wi-Fi-based communication.
- Cloud-based data logging using Google Sheets.
- Hardware and software integration.

## Future Improvements

- Real-time attendance dashboard.
- Date-wise attendance reports.
- Student database management.
- Web-based attendance monitoring.


## Developed By
Lakshmi Geeth Krishnan
## Project Gallery

### 1. Hardware Setup
![Hardware Setup](images/1.jpg)

### 2. RFID Attendance System
![RFID Scanning](images/2.jpg)

### 3. Google Sheets Attendance Output
![Attendance Output](images/3.jpg)

Electronics and Communication Engineering
