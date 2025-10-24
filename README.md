# 🌾 IoT-Based Smart Scarecrow (Strawman’s Eye)

## 📌 Project Overview  
**IoT-Based Smart Scarecrow** is an intelligent **IoT-enabled crop protection system** designed to monitor agricultural fields and prevent crop damage caused by animals or human intrusions.  
The system combines **motion detection**, **real-time image capture**, and **email notifications**, offering farmers a reliable and automated surveillance solution.

---

## ⚙️ Key Features  
- 📸 **ESP32-CAM Integration:** Captures images in real-time and transmits them via Wi-Fi.  
- 👁️ **PIR Motion Sensor:** Detects any motion in the field with high accuracy.  
- 🔄 **Servo Motor Mechanism:** Rotates between 0°–180° for wide-area coverage.  
- 📧 **Email Alert System:** Sends captured images to the farmer’s registered email via SMTP.  
- 💡 **Compact & Efficient:** Low-cost, low-power solution ideal for agricultural applications.

---

## 🧠 Working Principle  
1. The **PIR sensor** detects motion in front of it.  
2. The **ESP32-CAM** captures an image when motion is detected.  
3. The **servo motor** sweeps from 0° to 180° to cover a larger area.  
4. The captured image is sent to a registered **email address** via SMTP using Wi-Fi.  
5. The system resets and continues surveillance for the next motion event.

---

## 🔧 Hardware Components  
- **ESP32-CAM Module**  
- **PIR Motion Sensor (HC-SR501)**  
- **SG90 Servo Motor**  
- **Jumper Wires**  
- **5V Power Supply Module**  
- **Breadboard / PCB**  
- **Protective Enclosure or Mount**

---

## 💻 Software Requirements  
- **Arduino IDE**  
- **ESP32 Board Package**  
- **Required Libraries:**  
  - `ESP32_MailClient.h`  
  - `Servo.h`  
  - `WiFi.h`

---

## 🧩 Circuit Connections  

| Component | ESP32-CAM Pin |
|------------|---------------|
| PIR Sensor Output | GPIO 13 |
| Servo Signal | GPIO 12 |
| VCC | 5V |
| GND | GND |

---

## 🚀 System Operation  
1. Upload the Arduino code to the ESP32-CAM using an **FTDI programmer**.  
2. Connect to Wi-Fi and configure the **SMTP email credentials**.  
3. Deploy the setup in the agricultural field.  
4. Upon motion detection:  
   - The **servo motor** scans the area.  
   - The **ESP32-CAM** captures an image.  
   - The image is sent automatically to the registered **email inbox**.  
5. The system resets and continues monitoring.

---

## 📫 Output  
- Real-time motion detection  
- Captured image sent via email  
- Continuous 0°–180° scanning surveillance  

---

## 🧰 Technologies Used  
`ESP32-CAM` • `PIR Motion Sensor` • `Servo Motor` • `IoT` • `SMTP Email Automation`

---

## 🏁 Project Outcome  
This project successfully demonstrates an **IoT-based smart surveillance system** that enhances crop security by detecting intrusions and alerting farmers remotely through real-time image emails.

---

## 💡 Future Improvements  
- 🌙 Add **night vision** capability using IR LEDs  
- 📱 Integrate **SMS or Telegram bot alerts**  
- ☀️ Use **solar energy** for sustainable operation  

---

## 👨‍💻 Author  
**Ram Axay**  
🎓 *Electronics and Communication Engineering (ECE)*  
💼 *IoT | Embedded Systems | Smart Agriculture Enthusiast*  

---

⭐ *If you like this project, give it a star on GitHub!* ⭐
