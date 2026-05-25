# # 📌 AQMS
Air Quality Monitoring System

#  AQMS: Air Quality Monitoring System

![WhatsApp Image 2025-06-25 at 3 26 37 PM](https://github.com/user-attachments/assets/0b1f7509-bdda-455c-a5e9-569a00d2de95)

## 📊 About the Project

**AQMS** is an affordable, portable, IoT-enabled **Air Quality Monitoring System** built using the **ESP32 microcontroller** and multiple environmental sensors to monitor air pollutants in real time. It computes the **Air Quality Index (AQI)** and transmits the data to **ThingSpeak** Cloud at 15-second intervals. The setup also includes a real-time OLED display along with a compact **custom PCB design** for efficient system integration.

## 🎯 Features

- ✅ Real-time tracking of PM2.5, CO, NO₂, TVOCs, temperature, and humidity levels
- 📶 Wireless data transmission to ThingSpeak through Wi-Fi connectivity
- 📟 Integrated OLED screen for instant on-device readings
- 🔋 Operated using a rechargeable 3.7V Li-Po battery
- 📊 Live AQI computation with categorized air quality indication
- 🧠 Compact and modular PCB architecture designed using KiCad
## 🧱 Tech Stack / Hardware Used

| Category              | Components / Tools                                   |
|----------------------|------------------------------------------------------|
| 🧠 Microcontroller    | ESP32 (dual-core, built-in Wi-Fi)                    |
| 🌫️ PM2.5 Sensor       | Winsen ZPH02                                         |
| ⚠️ CO Sensor          | MQ-7                                                |
| 🧪 NO₂ Sensor         | DFRobot MEMS                                         |
| 🧴 TVOC Sensor        | Winsen ZP07-MP503                                    |
| 🌡️ Temp/Humidity      | DHT22 (AM2302)                                       |
| 💻 Display            | 0.96" OLED                                           |
| 🔋 Power              | Li-Po 3.7V Battery + MT3608 Boost Converter         |
| 🛠️ PCB Design Tool    | KiCad                                                |
| ☁️ Cloud Platform     | ThingSpeak                                           |
| 🧰 IDE                | Arduino IDE                                          |

## 🚀 Getting Started

### 🔧 Requirements 

Ensure the following prerequisites are completed before setup:

- Arduino IDE must be installed
- ESP32 board package should be added to the board manager
- Necessary libraries should be installed: 
   
   Adafruit_SSD1306

   Adafruit_GFX

   DHT Sensor Library

   MQ7

   ThingSpeak 

---


## 📸 Project Gallery

| View        | Image                                 |
|-------------|----------------------------------------|



||| Front Percpective ||| ![WhatsApp Image 2025-06-25 at 3 26 37 PM](https://github.com/user-attachments/assets/bebe23e6-71a9-4e11-be28-7e3b044c0930)

||| Back Percpective ||| ![WhatsApp Image 2025-06-25 at 3 26 38 PM](https://github.com/user-attachments/assets/c48af846-fdea-4b4c-851b-f4d3773a039f)

||| PCB Layout ||| ![Screenshot 2025-06-25 161154](https://github.com/user-attachments/assets/7347e775-a755-4eec-b577-11e33b4acf48)

||| Schematic ||| ![Screenshot 2025-06-25 162458](https://github.com/user-attachments/assets/460dbff1-d09d-496c-bf3d-fa7bc3538d5a)

||| 3D Preview |||![image](https://github.com/user-attachments/assets/01ba273b-7902-4d96-9812-8553479f7a00)

## ☁️ ThingSpeak Dashboard

![Screenshot 2025-06-25 161401](https://github.com/user-attachments/assets/61220e7c-916b-4f34-a8e9-f05d5bb6ce1f)



> 🔗 [ThingSpeak Live Channel](https://thingspeak.com/channels/your_channel_id)





