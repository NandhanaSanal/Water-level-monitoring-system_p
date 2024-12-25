# Water-level-monitoring-system_pWater Level Monitoring System Project

A Water Level Monitoring System is an embedded solution designed to monitor the water level in storage tanks, reservoirs, or any other water storage system. This system can automate the process of managing water levels, reducing human intervention and preventing issues like water wastage or pump damage due to dry running. It is widely used in households, agriculture, industries, and municipal water systems.

Objective The primary aim is to:

Monitor water levels accurately.
Automate the pump operation based on water levels.
Prevent overflow or dry running.
Provide visual and audible alerts when necessary.
System Description

The project consists of components like : Sensing Unit: The ultrasonic sensor measures the distance between the water surface and the sensor. This data is used to calculate the water level.

Processing Unit: A microcontroller (e.g., Arduino) processes the data from the sensor. It determines the water level and controls the pump based on preset thresholds. A relay module operates the water pump automatically.

Components Used

Ultrasonic Sensor (HC-SR04)
Arduino Uno
Relay Module
Water Pump
Power Supply
Working Principle

Measurement: The ultrasonic sensor sends a sound wave that reflects off the water surface and returns to the sensor. The time taken for the sound wave to return is used to calculate the distance.

Water Level Calculation: The total height of the tank is known. Water level = Total height - Distance measured by the sensor.

Data Processing: The microcontroller processes the distance data to calculate the water level percentage

Automation: If the water level is below the lower threshold, the pump turns on automatically. If the water level reaches the upper threshold, the pump turns off automatically

Advantages

Prevents water overflow and wastage.
Automates water management, saving time and effort.
Avoids pump damage due to dry running.
Reduces manual monitoring.
Low-cost and easy to implement.
Applications

Domestic Use
Agriculture
Industrial Use
Smart Cities
