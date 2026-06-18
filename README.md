# wet-dry-metal-detector-smart-waste-segregator-dustbin
AI-powered Smart Dustbin that auto-segregates Wet, Dry &amp; Metal waste using sensors. Built with Arduino + Metal Detector + Moisture sensor for cleaner, smarter cities.
# Smart Waste Segregator Dustbin ♻️

An IoT-based automated dustbin that segregates waste into **Wet, Dry, and Metal** categories in real-time using sensors. No human touch, no manual sorting.

### ✨ Features
- **3-Way Segregation**: Detects Wet waste via moisture sensor, Metal via metal detector, rest goes to Dry
- **Automatic Lid**: Opens on hand detection using IR/Ultrasonic sensor  
- **Real-time Classification**: <2 sec response time
- **Eco-Friendly**: Reduces manual waste handling + improves recycling

### 🔧 Hardware Used
| Component | Purpose |
| --- | --- |
| Arduino Uno/Nano | Main controller |
| Metal Detector Sensor | Detects metallic waste |
| Moisture/Humidity Sensor | Detects wet waste |
| IR/Ultrasonic Sensor | Hand detection for lid |
| Servo Motor | Opens/closes bins |
| 3 Storage Bins | Wet, Dry, Metal |

### ⚙️ How It Works
1. User puts waste near sensor
2. Metal detector checks first → If metal = Metal bin opens
3. If no metal → Moisture sensor checks → Wet/Dry decided  
4. Servo rotates to correct bin + lid closes

### 🚀 Future Upgrades
- Add GSM module to alert when bin is full
- LCD display for waste stats  
- Mobile app via Bluetooth


---
**Tech Stack**: Arduino C++, Sensors, Embedded Systems
