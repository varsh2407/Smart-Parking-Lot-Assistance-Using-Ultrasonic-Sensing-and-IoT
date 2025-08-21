An IoT-based smart parking management system that uses ultrasonic sensors to detect empty and occupied parking slots in real time. Sensor data is updated every 3 seconds and sent to the ThingSpeak cloud platform via API, where it is processed and displayed on a web interface:
🟢 Green → Slot Available
🔴 Red → Slot Occupied
This system reduces search time, improves parking efficiency, and can be scaled for smart city applications.
✨ Features
✅ Real-time slot detection with ultrasonic sensors
✅ Automatic refresh every 3 seconds
✅ Cloud integration via ThingSpeak API
✅ Web interface to display live parking status
✅ Scalable and smart city ready
🛠️ Tech Stack
Hardware: Ultrasonic Sensors, Microcontroller (ESP8266/ESP32/Arduino with Wi-Fi module)
Cloud: ThingSpeak API for IoT data management
Frontend: HTML, CSS, JavaScript (to visualize parking status)
Tools: Arduino IDE / PlatformIO

Installation & Setup
Connect ultrasonic sensors to the microcontroller.
Configure Wi-Fi credentials & ThingSpeak API key in the code.
Upload code via Arduino IDE/PlatformIO.
Open your ThingSpeak channel to view real-time sensor updates.
Access the web dashboard to visualize slot status (green/red).

Future Scope
Mobile app with ThingSpeak API integration 📱
Advanced analytics using MATLAB in ThingSpeak
Automatic billing/payment system
Integration with Google Maps for smart navigation
