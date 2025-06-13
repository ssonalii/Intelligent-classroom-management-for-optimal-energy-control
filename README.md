# Intelligent-classroom-management-for-optimal-energy-control
This project focuses on building an IoT-based Smart Classroom System that intelligently monitors and manages energy consumption and student presence using sensor data, automation, and real-time analytics. The system leverages Blynk IoT, NodeMCU, and various environmental sensors to provide an efficient, interactive, and sustainable classroom environment.

🔍 Problem Statement
Educational institutions face challenges in managing classroom resources efficiently. Energy wastage due to idle lighting/fans and lack of insights into classroom occupancy can lead to increased costs and environmental impact.

🎯 Objective
To develop a smart classroom solution that:

Automatically monitors and controls classroom appliances based on student presence.

Optimizes energy usage with real-time data.

Enhances the learning environment through smart automation and alerts.

⚙️ Technologies Used
Microcontroller: NodeMCU ESP8266

IoT Platform: Blynk (Mobile App & Cloud)

Sensors:

PIR Sensor (Motion Detection)

DHT11 Sensor (Temperature & Humidity)

LDR (Light Intensity)

Other Hardware:

Relay Module

LEDs, Fan, Bulb (simulated appliances)

Programming Language: C/C++ (Arduino IDE)

🧠 Features
Real-time monitoring of temperature, humidity, and motion.

Automatic control of lights and fans based on occupancy and environmental conditions.

Blynk dashboard for mobile-based control and data visualization.

Alerts for unusual behavior (e.g., high temperature, no student presence).

Blynk App Dashboard displays:

Live Temperature and Humidity readings

Switch controls for fans/lights

Occupancy Status

Energy-saving status indicators

📦 Installation & Setup
Install Arduino IDE and NodeMCU drivers.

Install required libraries:

Blynk

DHT Sensor Library

Configure your Wi-Fi credentials and Blynk Auth Token in the code.

Upload the code to NodeMCU.

Set up the Blynk mobile dashboard with appropriate widgets.

📈 Outcomes
Up to 30–40% reduction in energy usage during idle periods.

Enhanced classroom comfort and smart automation.

Scalable to multiple classrooms or buildings.

🌱 Future Scope
Integration with Machine Learning for predictive energy optimization.

Use of RFID or facial recognition for student authentication.

Cloud data logging for long-term analytics.
