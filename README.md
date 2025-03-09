# Perishable-food-monitoring

This project is a comprehensive monitoring system designed to track food appliances throughout the supply chain using embedded sensors, cloud integration, and real-time data visualization.

## Features
- **Sensor Integration**: Utilizes RTC DS1307 and DHT11 on ESP32 for accurate timekeeping, temperature, and humidity monitoring.
- **Cloud Integration**: Integrated IBM Cloud for IoT to efficiently manage, analyze, and visualize sensor data for enhanced real-time insights.
- **Data Publishing**: Uses MQTT protocol with PubSubClient to publish sensor data to IBM Cloud.
- **Time Synchronization**: Utilizes RTC for real-time tracking and timestamping of sensor data.

## Technologies Used
- **Embedded Systems**: ESP32, RTC DS1307, DHT11 Sensor
- **Cloud Platform**: IBM Cloud for IoT
- **Programming Languages**: C++

## Installation & Setup
1. **Hardware Setup:**
   - Connect RTC DS1307 and DHT11 sensor to the ESP32 board.
   - Ensure proper wiring and connections are established for data collection.

2. **IBM Cloud Setup:**
   - Create an IBM Cloud account and configure IoT services for data ingestion.
   - Establish device connections with ESP32 for data streaming.

3. **Code Deployment:**
   - Clone the repository containing the provided ESP32 code.
   - Update the WiFi credentials (`ssid` and `password`) and IBM Cloud credentials in the code.
   - Upload the code to ESP32 using Arduino IDE.

## Usage
- ESP32 reads temperature and humidity data from the DHT11 sensor.
- RTC provides accurate timestamps for each data entry.
- The data is published to IBM Cloud using MQTT protocol.
- Monitor sensor data via IBM Cloud dashboards for real-time insights.

## Contact
For inquiries or contributions, feel free to reach out!