# UpskillCampus

🌡️ Temperature and Humidity Monitoring System
📌 Project Overview:
This project is a Temperature and Humidity Monitoring System built using the ESP32 and the DHT22 Temperature and Humidity Sensor.
The system measures environmental temperature and humidity and displays the readings in real time on an SSD1306 OLED Display.
This project demonstrates how sensors and microcontrollers can be used to monitor environmental conditions efficiently.

🧰 Components Used:
ESP32 Microcontroller
DHT22 Temperature and Humidity Sensor
SSD1306 OLED Display
Breadboard
Jumper Wires
Power Supply
🔌 Circuit Connections:
DHT22 Sensor
Pin	Connection
VCC	3.3V (ESP32)
GND	GND
DATA	GPIO 4
OLED Display
Pin	Connection
VCC	3.3V
GND	GND
SDA	GPIO 21
SCL	GPIO 22

⚙️ Working Principle:
The DHT22 sensor measures temperature and humidity from the environment.
The sensor sends the data to the ESP32 microcontroller.
The ESP32 processes the data using the programmed code.
The processed values are displayed on the OLED display in real time.

📊 Example Output
Temperature: 24.00 °C
Humidity: 40.00 %
📷 Project Setup
![WhatsApp Image 2026-03-11 at 11 43 24 AM](https://github.com/user-attachments/assets/a04410a3-4078-4a06-858e-c8c4ce672f2d)

images/project_setup.jpg
<img width="763" height="739" alt="image" src="https://github.com/user-attachments/assets/e3bb2160-add2-4563-8d7d-ba35461b705c" />
<img width="604" height="579" alt="image" src="https://github.com/user-attachments/assets/04e348aa-465e-4041-afcb-32a8f0c3190a" />

The program reads data from the DHT22 sensor and displays the readings on the OLED screen using I2C communication.

🚀 Applications

Weather monitoring systems
Smart homes
Greenhouse monitoring
Industrial environmental monitoring
Laboratories and storage facilities

✅ Conclusion

The Temperature and Humidity Monitoring System successfully measures environmental conditions and displays them in real time. The project demonstrates the practical use of sensors and microcontrollers in environmental monitoring systems.

📚 References

ESP32 Documentation

DHT22 Sensor Datasheet

Embedded Systems Learning Resources
