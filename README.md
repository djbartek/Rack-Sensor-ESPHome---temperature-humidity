1U Rack mounted temperature & humidity sensor. Uses ESPHome to send data to HomeAssistant. Can work also without a network.

Mounted to the right side rail. Needs right angled micro usb cord to power, straight ones do not seat properly with rack rail.

Shows name ("Rack Sensor" - easily changed in czujnik-rack.yaml file), time, temperature & humidity and connection with HomeAssistant:
- "((o))" for connected
- "I" for not connected

If temperature or humidity lacks digit set GHT22 less frequent refresh rate.

Shows "Error" if it's not getting data from the DHT22 sensor.


Needs:
- DHT22 temperature & humidity sensor
- ESP-WROOM-32 with WiFi (micro USB)
- OLED 1,3″ 128x64px I2C (4pin)
- About 50g of filament
- 6 screws

Connection guide for dummies:
- Inside there is enough space to use female-female connection wires, no need to solder to any of the components! (as long they have male pin connectors)
- Connect ESP32 3.3V pin to OLED VCC pin AND DHT22 VCC pin
- ConnectESP32 GND pin to DHT GND pin AND OLED GND pin
- Connect DHT22 Data pin to ESP32 pin21
- Connect OLED SDA pin to ESP32 pin18
- Connect OLED SCL pin to ESP32 pin19
