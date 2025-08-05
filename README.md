# RFID_based_car_parking_management_system
This project implements an RFID-based automated car parking system using Arduino and an RFID reader (MFRC522). It allows authorized vehicles (with RFID tags) to enter/exit the parking lot while tracking available slots.

Features
✔ RFID Authentication – Only registered RFID tags grant access.
✔ Slot Availability Display – Shows free/total parking slots on an LCD.
✔ Automatic Gate Control – Servo motor opens/closes the barrier.
✔ Data Logging – Stores entry/exit timestamps (optional with EEPROM/SD card).

Hardware Requirements
Arduino Uno/Nano

RFID Module (MFRC522) + Tags

Servo Motor (for gate control)

LCD (16x2 I2C)

IR Sensors (for slot detection)

Buzzer (for alerts)

Setup
Connect RFID to Arduino via SPI.

Attach servo to the barrier gate.

Place IR sensors in parking slots.

Upload code (RFID_Parking_System.ino) and register tags.

Usage
Scan RFID tag → Gate opens if valid.

IR sensors update slot count on LCD.

Admin mode (optional) to add/remove tags.

Future Scope
Cloud database for remote monitoring.

Mobile app for slot booking.

Number plate recognition integration.
