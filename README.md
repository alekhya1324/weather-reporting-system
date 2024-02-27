# weather-reporting-system
# IoT Weather Reporting System with Arduino

This project allows you to create a simple IoT-based weather reporting system using Arduino, DHT22 sensor for temperature and humidity, and BMP180 or BMP280 sensor for pressure.

## Hardware Requirements:
- Arduino board
- DHT22 sensor
- BMP180 or BMP280 sensor
- WiFi module (e.g., ESP8266)

## Software Requirements:
- Arduino IDE
- Adafruit BMP085 library
- DHT sensor library
- WiFi library

## Setup Instructions:

1. **Install Libraries:**
   - Open Arduino IDE.
   - Navigate to Sketch > Include Library > Manage Libraries.
   - Search for "Adafruit BMP085" and "DHT sensor library" and install them.

2. **Connect Hardware:**
   - Connect DHT22 sensor to pin 2 on the Arduino.
   - Connect BMP180 or BMP280 sensor to the respective pins on the Arduino.
   - Connect the Arduino to the WiFi module.

3. **Configure WiFi and Server:**
   - Update the `ssid` and `password` variables in the Arduino code with your WiFi credentials.
   - Set the `serverIP` variable to the IP address of your server.

4. **Upload Code:**
   - Connect Arduino to your computer using a USB cable.
   - Open the Arduino IDE, load the provided code, and upload it to the Arduino.

5. **Server Setup:**
   - Create a server script (e.g., using Node.js, Python, or PHP) to handle incoming data.
   - Implement an endpoint (e.g., "/updateWeatherData") to receive the data sent by the Arduino.

6. **Monitor Data:**
   - Open the Arduino Serial Monitor to view the data being sent to the server.
   - Ensure the server script is properly receiving and processing the data.

7. **Customization:**
   - Modify the code according to your specific requirements.
   - Implement additional features or visualization as needed.

8. **Run the Project:**
   - Power up the Arduino and observe the data being sent to the server at regular intervals.

Enjoy your IoT Weather Reporting System with Arduino!
