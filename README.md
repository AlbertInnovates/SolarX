# ☀️ Smart Solar Monitoring System (IoT + Cloud + Data Visualization)

A real-time IoT-powered solar energy monitoring system that collects, analyzes, and visualizes data from solar panels — empowering users to track energy performance, optimize usage, and promote sustainable living.

Built with a blend of **embedded hardware**, **Python-based data analytics**, and **cloud infrastructure**, this project turns raw solar data into actionable insight.

---

## 🔍 Project Objectives

- 📡 **Real-time monitoring** of voltage, current, power output, and temperature
- ☁️ **Cloud integration** for remote access using Firebase or AWS IoT
- 📈 **Data visualization dashboard** using Python Flask and JavaScript
- 🧠 Leverage **IoT + data science** for optimized energy usage in rural areas

---

## ⚙️ A. Hardware Components

| Component             | Function                                       |
|----------------------|------------------------------------------------|
| Solar Panels          | Converts sunlight to electrical energy         |
| ESP32 / Arduino       | Microcontroller for data collection & control |
| ACS712 Current Sensor | Measures electrical current                    |
| Voltage Divider       | Measures panel voltage                         |
| DHT11 Temp Sensor     | Monitors surrounding temperature               |
| ESP8266 WiFi Module   | Sends data wirelessly to the cloud             |
| LCD Display (optional)| Shows live values locally                     |

---

## 🧑‍💻 B. Software & Programming

| Task                     | Language / Tools                             |
|--------------------------|----------------------------------------------|
| Microcontroller Code     | **C++** (Arduino IDE or PlatformIO)          |
| Data Processing          | **Python** (NumPy, Pandas)                   |
| Cloud Connectivity       | **Firebase** / **AWS IoT Core**              |
| Dashboard Development    | **Python Flask/Django**, **JavaScript**      |

---

## 🧪 System Workflow

1. **Sensors** collect voltage, current, temperature data  
2. **ESP32** or **Arduino** processes signals and formats data  
3. Data is sent via **WiFi module** to a **cloud server**  
4. Remote users can view trends and real-time stats via a **web dashboard**  

---

## 📊 Dashboard Features

- 📍 Live voltage/current readings
- 📅 Historical trends of power output
- 🔥 Temperature-vs-efficiency analysis
- 📡 System status alerts (offline, overheating, etc.)

---

## 🌍 Why This Matters

> As energy access continues to challenge off-grid communities, smart solutions like this project offer **clean, data-driven energy equity** — especially in rural Africa.

This work builds on my practical experience supplying solar panels in Rutonde Cell (Rwanda) and now integrates **IoT + data science** to enable **real-time optimization**.

---

## 📌 Future Enhancements

- ⚙️ Add battery-level monitoring  
- 🌐 Deploy dashboard on a public server (Heroku, Netlify)  
- 🔁 Automate panel tilt adjustment using servo motors  
- 🔒 Add user authentication to dashboard
