# LED-lamp-tester

Met dit esp32 project meten we met behulp van 2 digitale sensoren (DH1750 en BMP280) de lichtsterkte (lux) en de temperatuur(°C).
De sensoren zijn aangesloten via I2C aan de esp32.
De waarden van de senoren wordt ook weergegeven op uw smartphone via de Blynk app.
Ik heb gekozen voor de esp32 omdat deze al een wifi module heeft.

Je begint van de esp32 naar Oled 
| esp32 pin  | Oled |   
| ------------- | ------------- |
| 3V3  | VCC  |
| GND  | GND  | 
| D21  | SCL  |
| D22  | SDA  |

Dan word er doorgelust van Oled naar BH1750
       
| Oled | BH1750 |
| ------------- | ------------- |
| VCC | VCC |
| GND  | GND  | 
| SCL  | SCL  |
| SDA  | SDA  |

En als laatste lus je door van BH1750 naar BMP280

| BH1750 | BMP280|
| ------------- | ------------- |
| VCC | VCC |
| GND  | GND  | 
| SCL  | SCL  |
| SDA  | SDA  |

[embed]http://example.com/file.pdf[/embed]
