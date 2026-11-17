# ESP32 Analog Sensor Readings

Arduino C++ sketches for reading analog sensors with an ESP32
(Heltec board) and printing results over serial.

## Projects

### 1. Soil moisture sensor
- Reads the sensor on ADC1 channel 7 (GPIO 35), 12-bit resolution.
- Scales the raw ADC value (0-4095) to a 0-100 % moisture value.

### 2. Temperature sensor (MCP9700A)
- Reads the sensor on ADC1 channel 4 (GPIO 32).
- Converts voltage to °C: T = (Vout - 0.5 V) / 0.01 V.

## Hardware
- Heltec ESP32 board
- Soil moisture sensor (analog output)
- MCP9700A temperature sensor

## Usage
Open the .ino file in Arduino IDE, select the ESP32 board,
upload and open the Serial Monitor at 115200 baud.

## About
Personal project developed for learning and prototyping
IoT sensor nodes. Not affiliated with any company or client.
