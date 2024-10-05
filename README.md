# IOT Data Visualization Backend & ESP32 Code

This repository contains the Django server backend for storing temperature and humidity data and the Arduino code for ESP32 devices. The ESP32 devices connect via Bluetooth (BLE), receive WiFi credentials, and send sensor data to the server for storage and real-time visualization.

## :dart: About ##

The Django server handles storing the temperature and humidity data sent by ESP32 devices. The ESP32 devices are programmed using Arduino code to connect to WiFi and communicate with the server. The data is displayed via charts for real-time visualization.

## :sparkles: Features ##

- **Django Backend**: Stores temperature and humidity data from ESP32 devices.
- **ESP32 Arduino Code**: Enables ESP32 devices to connect to WiFi and transmit sensor data.
- **Real-Time Data Visualization**: Displays the collected data on a frontend interface (integrated with a mobile app in a separate repository).

## :rocket: Technologies ##

The following tools and frameworks are used in this project:

- [Django](https://www.djangoproject.com/) - Web framework for the backend.
- [Arduino](https://www.arduino.cc/) - Platform for programming the ESP32 devices.
- [ESP32](https://www.espressif.com/en/products/socs/esp32) - Microcontroller for collecting and transmitting sensor data.

## :white_check_mark: Requirements ##

To run this project, ensure that you have the following installed:

- [Python 3.8+](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Arduino IDE](https://www.arduino.cc/en/software)
- ESP32 hardware

## :checkered_flag: Starting the Django Server ##

Follow these steps to run the Django backend locally:

```bash
# Clone this repository
$ git clone https://github.com/Piiii31/IOT-DATA-Visualization-Backend-CodeESP

# Navigate to the backend directory
$ cd IOT-DATA-Visualization-Backend-CodeESP

# Install dependencies
$ pip install -r requirements.txt

# Run database migrations
$ python manage.py migrate

# Start the Django development server
$ python manage.py runserver

# The server will be running at http://localhost:8000
:electric_plug: Uploading Code to ESP32
Open the Arduino IDE.
Install the required ESP32 board libraries from the Arduino Boards Manager.
Open the provided .ino file from the ESP32_Code directory.
Connect your ESP32 device to your computer via USB.
Select the appropriate board and port in the Arduino IDE.
Upload the code to your ESP32.

:handshake: Contributions
Feel free to contribute by submitting a pull request or opening an issue.

:mailbox_with_mail: Contact
For any inquiries, reach out to: meddeb65@gmail.com

<p align="center"> Made with :heart: by <a href="https://github.com/Piiii31" target="_blank">Piiii31</a> </p> ```
This template includes sections for your Django backend and ESP32 Arduino code, explaining how to set them up and run them.
