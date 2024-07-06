1U Rack mounted temperature & humidity sensor. Uses ESPHome to send data to HomeAssistant. Can work without a network.

You need:
- DHT22 temperature & humidity sensor
- ESP-WROOM-32 with WiFi (micro USB)
- OLED 1,3″ 128x64px I2C (4pin)
- About 50g of filament

Mounted to the right side rail. Needs right angled micro usb cord to power, straight ones do not seat properly with rack rail.

Shows name ("Czujnik Rack" - easily changed), time, temperature & humidity and connection with HomeAssistant:

"((o))" for connected
"I" for not connected

If temperature or humidity lacks digit set GHT22 less frequent refresh rate.
Shows "Error" if it's not getting data from the DHT22 sensor.
