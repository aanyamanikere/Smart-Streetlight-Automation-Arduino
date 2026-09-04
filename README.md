# Smart-Streetlight-Automation-Arduino
An Arduino-based multi-sensor simulation built in Tinkercad that integrates ambient light detection (LDR) and motion tracking (PIR) to demonstrate dynamic, energy-efficient street lighting and security alerts.  

Project Overview
- Daytime Mode: System remains completely off to conserve power.
- Night Standby Mode: LDR detects ambient darkness and activates the LED at low brightness (20% PWM).
- Active Motion Alert: PIR sensor detects movement, triggering 100% LED brightness and an audible buzzer alert.

**Hardware & Components**
- Arduino Uno Microcontroller
- Light-Dependent Resistor (LDR) + 10kΩ Resistor (Voltage Divider)
- Parallax PIR Motion Sensor
- LED + 220Ω Current-Limiting Resistor
- Piezo Buzzer  
