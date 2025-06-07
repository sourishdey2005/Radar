# 🚀 Arduino-Based Ultrasonic Radar System  

## 📌 Overview  
This project is an **Arduino-powered radar system** using an **HC-SR04 ultrasonic sensor** to detect objects and visualize their positions in real-time. The system scans the environment by rotating the sensor with a **servo motor**, measuring distances, and displaying the results on an **OLED screen or a Processing-based GUI**.  

## 🔧 Features  
✅ **Real-Time Object Detection** – Continuously scans and detects obstacles within range  
✅ **Servo-Controlled Scanning** – Rotates the ultrasonic sensor for a **180° field of view**  
✅ **Distance Measurement** – Uses **HC-SR04** to calculate object distances accurately  
✅ **Graphical Visualization** – Displays radar-like output on an **OLED screen or PC GUI**  
✅ **Customizable Range & Sensitivity** – Adjustable detection parameters  

## 🛠 Hardware Requirements  
- **Arduino Uno** (or compatible board)  
- **HC-SR04 Ultrasonic Sensor**  
- **SG90 Servo Motor**  
- **OLED Display (Optional)**  
- **Jumper Wires & Breadboard**  

## 🔌 Wiring Diagram  
| Component | Arduino Pin |  
|-----------|------------|  
| HC-SR04 Trigger | D9 |  
| HC-SR04 Echo | D10 |  
| Servo Motor | D6 |  
| OLED Display (SDA) | A4 |  
| OLED Display (SCL) | A5 |  

## 💻 Software & Libraries  
- **Arduino IDE** (for coding & uploading)  
- **Processing** (for graphical radar visualization)  
- **Libraries:** `Servo.h`, `NewPing.h`, `Adafruit_GFX.h`, `Adafruit_SSD1306.h`  

## 🚀 Installation & Usage  
1️⃣ **Clone the repository**  
