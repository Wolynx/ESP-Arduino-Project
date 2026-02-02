# ESP32 Multi-Function Smart Device

This project is a multi-functional embedded system developed on the ESP32
platform. It combines multiple interactive applications into a single
menu-driven interface using an OLED display and physical buttons.

The system is designed to demonstrate real-world embedded systems concepts
such as hardware–software integration, state management, timing control,
and user interaction on resource-constrained devices.

---

## 🧩 Features

### 📋 Menu-Based User Interface
- OLED (SH1106) based graphical menu
- Button-controlled navigation (UP, DOWN, LEFT, RIGHT, SELECT)
- Modular application switching

### 🐍 Snake Game
- Grid-based movement system
- Collision detection (walls & self)
- Score and high-score tracking
- Adjustable game update interval

### 🧠 Reflex Game
- Reaction-time based gameplay
- Direction-based user input validation
- Best reaction time tracking
- Timer-controlled game session

### 🌡️ Weather Monitor
- Temperature and humidity measurement using DHT11
- Real-time sensor data display

### ⚙️ Servo Motor Control
- Interactive angle control (0–180°)
- Visual progress bar representation
- ESP32 PWM servo control

### 🧮 Calculator
- Button-based virtual keypad
- Expression parsing with operator precedence
- Supports +, −, ×, ÷ operations

### ⏱️ Timer / Countdown
- Minute & second based configuration
- Real-time countdown display
- Audible alarm using buzzer
- Restart and stop functionality

### 🔘 Button Test & Calibration
- Live button state visualization
- Hardware input validation tool

---

## 🛠️ Hardware Used
- ESP32
- SH1106 OLED Display (I2C)
- DHT11 Temperature & Humidity Sensor
- Servo Motor
- Buzzer
- 5× Push Buttons

---

## 🧠 Technical Highlights
- State-based application control
- Efficient use of `millis()` for timing
- Modular function design
- Grid-based game logic
- Embedded input handling with debouncing
- Resource-aware UI rendering

---

## 🧪 Libraries Used
- Arduino Core for ESP32
- U8g2 (OLED graphics)
- DHT Sensor Library
- ESP32Servo

---

## 🎯 Purpose
This project was developed to improve practical embedded systems skills
beyond academic coursework and to gain hands-on experience in designing
interactive, real-time microcontroller applications.

---

## 👤 Author
**Volkan Özdemir**  
Electrical & Electronics Engineering Student  

🔗 GitHub: https://github.com/Wolynx  
🔗 LinkedIn: https://www.linkedin.com/in/ozdemirvolkantech
