# solar-panel-current-voltage-temperature-measurement-device
# Solar Panel Current, Voltage &amp; Temperature Measurement Device (ESP32)  This project is focused on developing a monitoring device for **solar panels** using the ESP32 microcontroller. 
<br>
The system measures three key parameters of a solar panel:

- **Voltage** – using a resistive voltage divider circuit connected to the ESP32 ADC.  
- **Current** – using a current sensor (e.g., INA219 / ACS712) for accurate current flow measurement.  
- **Temperature** – using a digital temperature sensor (e.g., DS18B20 / DHT22) to monitor panel surface temperature.

## Features
- Real-time measurement of **voltage, current, and temperature**.  
- Data displayed on **serial monitor / OLED display / web dashboard** (configurable).  
- ESP32 Wi-Fi support for **IoT-based monitoring (MQTT/HTTP/Thingspeak/Node-RED)**.  
- Low-power consumption with support for sleep modes.  
- Calibration-friendly design for accurate results.  

## Applications
- Solar panel **performance monitoring**.  
- Early detection of **faults or inefficiency**.  
- Educational and research projects on **renewable energy systems**.  

## Hardware Requirements
- ESP32 Development Board  
- Voltage divider circuit  
- Current sensor (INA219 / ACS712 / shunt-based)  
- Temperature sensor (DS18B20 / DHT22)  
- OLED / LCD display (optional)  

## Future Enhancements
- Integration with **cloud dashboards** (Grafana, Thingspeak, Blynk).  
- Data logging to **SD card / Google Sheets**.  
- Adding **MPPT (Maximum Power Point Tracking)** support.  
