# Oled I2C Display
We are using an I2C display to be able to visualize the different options available when using the AudioScope.

<img width="276" height="276" alt="ChatGPT Image 19 ene 2026, 12_48_54" src=https://github.com/2ME3Elektronika/25-26_AudioScope/blob/e56743320319c842e81f9add19bd381904dc9f85/Material/Oled%20I2C%20Display%20128x64%200%2C96%20in..png />

## Connections
- **VCC:** It is supllied with 5v by the 5v 10A power supply.
- **GND:** It is conected to the GND of the power supply.
- **SDA (Serial Data):** it is connected to the pin SDA of the adafruit hat.
- **SCL (Serial Clock):** it is connected to the pin SCL of the adafruit hat.

# Oled I2C Rotatory Encoder
The rotatory encoder is used to select between the different options that the oled i2c display gives us.

<img width="266" height="266" alt="ChatGPT Image 19 ene 2026, 12_48_54" src=https://github.com/2ME3Elektronika/25-26_AudioScope/blob/e56743320319c842e81f9add19bd381904dc9f85/Material/I2C%20Rotatory%20Encoder.png />

## Connections
- **VCC:** It is supplied with 5v by the 5v 10A power supply.
- **GND:** It is conected to the GND of the power supply.
- **SDA (Serial Data):** it is connected to the pin SDA of the adafruit hat.
- **SCL (Serial Clock):** it is connected to the pin SCL of the adafruit hat.

# I2S Microphone
This microphone is used to be able to test that the AudioScope is working properly.

<img width="266" height="266" alt="ChatGPT Image 19 ene 2026, 12_48_54" src=https://github.com/2ME3Elektronika/25-26_AudioScope/blob/e56743320319c842e81f9add19bd381904dc9f85/Material/I2S%20SPH0645%20Microphone.png />

## Connections
- **VCC:** It is supplied with 3,3v that come out of the regulator.
- **GND:** It is conected to the GND of the power supply.
- **BCLK:** It is conected to the GPIO 18 of the adafruit hat
- **LRCL/WS:** It is conected to the GPIO 19 of the adafruit hat
- **DOUT/SD:** It is conected to the GPIO 20 of the adafruit hat
- **Optional L/R (Channel selection):** In order to have a secundary sound channel it is conected to the GND of the power suplly.
