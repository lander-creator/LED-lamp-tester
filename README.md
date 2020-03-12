# LED-lamp-tester

![LED tester foto](https://user-images.githubusercontent.com/61006702/76534560-f0ae5a00-6479-11ea-9dd1-58c75df989b1.jpg)


Met dit esp32 project meten we met behulp van 2 digitale sensoren (DH1750 en BMP280) de lichtsterkte (lux) en de temperatuur(°C).
De sensoren zijn aangesloten via I2C aan de esp32.
Ik heb gekozen voor de esp32 omdat deze al een wifi module heeft.
# De waarden van de senoren wordt ook weergegeven op uw smartphone via de Blynk app.

![Screenshot_20200312-154120_Blynk](https://user-images.githubusercontent.com/61006702/76534837-513d9700-647a-11ea-87b2-c2f6803c4f80.jpg)

# Lijstje met je gebruikte pinnen:

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

# Aansluitschema:
[LED tester schema.pdf](https://github.com/lander-creator/LED-lamp-tester/files/4324876/LED.tester.schema.pdf)
