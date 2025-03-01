# RFID-Based Attendance System Using IoT

## Problem Statement
Traditional attendance methods, such as manual registers or biometric systems, can be time-consuming and error-prone. Our project solves this problem by using RFID technology to mark attendance instantly and store it in Google Sheets using IoT, making the process more accurate and accessible from anywhere.

## How It Works
Our system consists of an RFID reader and RFID tags assigned to individuals. When a person scans their RFID tag on the reader, the system records their attendance with a timestamp. The ESP8266 Wi-Fi module connects to the internet and updates this data in real-time on Google Sheets. This ensures a digital record of attendance, which can be accessed from anywhere.

## Components Used
- **RFID Reader (RC522)** – Reads the RFID tag data.
- **RFID Tags** – Unique IDs assigned to users.
- **ESP8266 Wi-Fi Module** – Sends data to Google Sheets via the internet.
- **Google Sheets API** – Stores and displays attendance data in real-time.
- **Power Supply** – Provides power to the components.

## Features
- **Automated Attendance Recording** – Eliminates manual errors and reduces time spent on attendance.
- **Real-Time Data Updates** – Attendance records are updated instantly on Google Sheets.
- **Remote Access** – Data can be accessed from anywhere with an internet connection.
- **Secure and Reliable** – RFID-based authentication ensures accuracy.

## Why It’s Useful
This project is highly beneficial for schools, offices, and organizations where attendance needs to be recorded accurately and efficiently. It eliminates manual errors, saves time, and provides real-time access to attendance records, making management easier.

## Setup Instructions
1. **Connect the Hardware:**
   - Wire the **RC522 RFID Reader** to the **ESP8266**.
   - Power the circuit using a **regulated power source**.
2. **Flash the ESP8266 Code:**
   - Use **Arduino IDE** or another suitable environment.
   - Install necessary libraries like `MFRC522`, `ESP8266WiFi`, and `HTTPSRedirect`.
3. **Configure Google Sheets API:**
   - Create a Google Sheet for attendance.
   - Enable Google Apps Script to handle incoming data.
   - Generate an API key and set up HTTP requests in the ESP8266 code.
4. **Deploy and Test:**
   - Scan an RFID tag to verify that attendance is recorded correctly.
   - Check real-time updates in the Google Sheet.

## Conclusion
In conclusion, our **RFID-Based Attendance System Using IoT** provides an efficient, accurate, and automated solution for tracking attendance. By leveraging RFID and IoT, this system ensures seamless and real-time record-keeping, making attendance management hassle-free.

## Future Enhancements
- **Integration with a Mobile App** for better accessibility.
- **Notification System** to alert users when their attendance is marked.
- **Data Analytics** for generating attendance reports and insights.


