# Nextion-yoradio ESP32S3

Radio internetowe oparte na esp32S3 oraz wyświetlaczu Nextion NX4024K032 (dotyk)

Oprogramowanie modyfikowałem czyli:
- Mapowaniem polskich i słowackich znaków na 8-bitowe kody (UTF-8 na Nextion8869-2)
- Zmiana czcionki zegara w Nextion NX4024K032
- Dodanie czcionki z polskimi i słowackimi ogonkami do Nextion NX4024K032
- inne

![20250407_181651](https://github.com/user-attachments/assets/bf113f71-511a-4dd9-99e2-db6248836df8)
![20250410_103805](https://github.com/user-attachments/assets/2743f537-c380-493f-aae5-be3067fee9d2)

Podłaczenie Nextion NX4024K032 do ESP32S3 oraz Modułu dekodera DAC PCM5102A (I2S)

#define NEXTION_RX			16  //TX Nextion → GPIO16 (RX) na ESP32-S3

#define NEXTION_TX			17  //RX Nextion → GPIO17 (TX) na ESP32-S3

#define I2S_DOUT			  9

#define I2S_BCLK			  3

#define I2S_LRC			    1
