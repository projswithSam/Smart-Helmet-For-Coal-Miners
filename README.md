# Smart-Helmet-For-Coal-Miners
OBJECTIVE AND FUNCTIONALITIES:
Detection of Harmful Gases: The wearable device should be able to detect high levels
of dangerous gases and immediately alert the miner and the control room;
Health Monitoring: Track vital signs like heart rate, temperature, and oxygen levels
of the miners;
Real-Time Alerts: The device should be able to provide immediate audible
or vibration-based warnings to miners;
Durability and Ergonomics: The device should be durable enough to withstand the
harsh conditions of coal mines while being comfortable to wear for long periods;
Communication: The device should be able to communicate data to a central system
in real-time for ongoing safety analysis and decision-making.

ARCHITECTURAL MODULES NEEDED:
1. Gas Detection Module
Function: Detects harmful gases like LPG, propane, methane, and
smoke using the MQ2 sensor and triggers alerts if gas levels exceed safe
limits.
2. Temperature and Humidity Monitoring Module
Function: Monitors the surrounding temperature and humidity using the
DHT11 sensor and provides data to ensure environmental safety

3. Distance Measurement Module
Function: Measures the distance between the helmet and nearby objects
using the HC-SR04 ultrasonic sensor, useful for detecting proximity to
walls or hazards.
4. Alert System Module
Function: Activates a buzzer to provide auditory alerts when dangerous
gas levels, extreme temperatures, or proximity hazards are detected.
5. Power Management Module
Function: Manages the power supply from the 9V battery to the Arduino
Nano and other sensors, ensuring consistent operation.
6. Data Processing and Control Module
Function: Arduino Nano processes sensor data and controls the
operation of other modules (such as triggering the buzzer) based on the
input from sensors.
7. Monitoring and Debugging Module
Function: Displays sensor data and system status on the Serial Monitor
in the Arduino IDE for real-time monitoring and debugging during
development or testing.

REQUIREMENTS:
Hardware:-
MQ2 Gas Sensor
DHT11 Temperature and Humidity
Sensor HC-SR04 Ultrasonic Sensor
Arduino Nano
9V Battery
Buzzer
Leather Belt

Software:-
Arduino Integrated Development Environment (IDE)
C/C++ (Arduino Language)

Observations on the Implementation of Smart Safety Helmet for
Coal Miners
1. Effective Hazard Detection:
• Utilized sensors (e.g., temperature, gas, IR) successfully detect 
environmental hazards like toxic gases, excessive heat, and obstructions.
2. Real-Time Monitoring:
• Continuous data collection enables real-time monitoring of miners' safety conditions.
• Alerts triggered by threshold breaches ensure timely preventive action.
3. Enhanced Safety:
• Immediate audio or visual alerts from the buzzer improve response time to
emergencies.
4. Compact Design:
• Integration of DHT11 and other sensors within the helmet ensures lightweight
and user-friendly equipment.
5. Power Consumption:
• Requires efficient power management to sustain extended underground operations.
6. Scalability:
• Can be further enhanced with IoT connectivity for centralized monitoring.
7. Challenges:
• Environmental factors (e.g., dust and humidity) may impact sensor performance.
• Requires regular maintenance and calibration of sensors for accuracy.
8. Potential Benefits:
• Improves miners' safety and reduces risks of workplace accidents in coal mines.
• Facilitates compliance with safety standards and regulations.




