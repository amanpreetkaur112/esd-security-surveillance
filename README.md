# Anti-Theft Surveillance Camera 🚨📷

A smart, AI-based surveillance system designed to detect and deter vehicle thefts in real-time using ESP32-CAM, motion sensors, and cloud integration.

## 🔍 Overview

This project presents a cost-effective, AI-powered surveillance camera system that identifies unauthorized activity around vehicles or property. It instantly alerts the user and uploads the captured footage to the cloud, enabling remote access and long-term storage.

## 🎯 Features

- Real-time object/motion detection
- Live camera feed via ESP32-CAM
- Instant alerts via mobile notifications/email
- Secure cloud storage of video evidence
- Compact, modular design for easy installation
- Expandable for smart homes and public security

## 🛠️ Tech Stack

- **Hardware:** ESP32-CAM, Motion/Touch Sensors, FTDI Module
- **Software:** Python, OpenCV, Firebase
- **AI:** YOLOv5 or custom object detection model
- **Cloud:** Firebase Realtime DB / Google Cloud Storage
- **Communication:** WiFi (via ESP32), Serial (FTDI)

## 🧰 Hardware Requirements

- ESP32-CAM module
- FTDI Programmer (USB to TTL)
- PIR Motion Sensor / Touch Sensor
- MicroSD Card (for local storage backup)
- Power Supply (Battery/USB)

## 🚀 Setup Instructions

1. **Flash the ESP32-CAM** with your Arduino IDE or VS Code (PlatformIO).
2. Connect the sensor to GPIO pins and power up the ESP32-CAM.
3. Deploy Python backend on a local server or Raspberry Pi for video processing (optional).
4. Link to Firebase for real-time alerts and video uploads.
5. Customize the mobile app (or use Firebase Alerts) for notifications.

## 📱 Alert Workflow

1. Motion or touch is detected.
2. ESP32-CAM captures footage.
3. Python backend (or onboard model) processes the frames.
4. Alert is sent to the user with timestamp and footage.
5. Data is stored securely in the cloud.

## 💡 Use Cases

- Personal vehicle surveillance
- Apartment/mall parking lot monitoring
- Fleet management security
- Smart home integration

## 📈 Future Enhancements

- Facial and license plate recognition
- Voice command support
- SMS/Call integration
- Solar power module for remote areas
- Mobile app with live feed and playback

## 👨‍💻 Team Members

- Nitish Kumar – 211001001079
- Amanpreet Kaur – 211001001032
- Soumya Upadhyay – 21100100106
- Soukarjo Kr. Das – 211001001004
- Anusri Chowdhury – 211001001017

## 📄 License

This project is for academic and educational purposes.

---
