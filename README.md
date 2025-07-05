#  ESP-AirEcoSystem: Wireless Air Monitoring Eco-System using ESP32

ESP-AirEco is a scalable, real-time air monitoring eco-system built using two ESP32 development boards. The system monitors **LPG (via MQ6)**, **air quality (via MQ135)**, **temperature & humidity (via DHT22)**. It uses **ESP-NOW** for low-power wireless communication and **Blynk IoT Cloud** for mobile notifications and data visualization. A local **OLED screen** displays live environmental metrics.

 📦 Features

- 🧪 **LPG Gas Monitoring** using MQ6 sensor
- 🌫️ **Air Quality Monitoring** using MQ135 sensor
- 🌡️ **Temperature & Humidity Sensing** via DHT22
- 📲 **Mobile App Alerts** via Blynk Cloud
- 🔔 **Buzzer Alert** when gas levels are high
- 🖥️ **OLED Display** for real-time values
- 📡 **ESP-NOW Wireless Communication** between sensor node and main node
- ⚡ **Low Power & Scalable**: add more sensor nodes in future


## ⚙️ Hardware Specifications

**Sensor node(ESP32 #1)**
| **ESP32 Dev Board** | Wi-Fi/Bluetooth microcontroller |
| **MQ6 Sensor** | LPG/Butane/Propane gas detection |
| **Power** | 5V via USB or regulated source |
| **Communication** | ESP-NOW (STA Mode) |

### 🔹 Main Node (ESP32 #2)

| Component | Description |
|----------|-------------|
| **ESP32 Dev Board** | Wi-Fi + ESP-NOW dual mode |
| **MQ135 Sensor** | Measures air quality/pollution |
| **DHT22 Sensor** | Temperature & Humidity sensor |
| **OLED 0.96" (I2C)** | Displays sensor readings |
| **Buzzer** | Audible alert on gas detection |
| **Power** | 5V via USB or regulated source |
| **Connectivity** | Wi-Fi for Blynk + ESP-NOW for local node |







