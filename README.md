# Var:Pivo main controller PCB

| Device       | Pin label | Connector pin  | GPIO pin | Board pin | Comment                                                                  |
| ------------ | --------- | -------------- | -------- | --------- | ------------------------------------------------------------------------ |
| Scale        | GND       | 2              |          | 14        |                                                                          |
| Scale        | DT        | 3              | GPIO24   | 18        | HX711                                                                    |
| Scale        | SCK       | 4              | GPIO23   | 16        | HX711                                                                    |
| Scale        | VCC\_5    | 5              |          | 2         |                                                                          |
| 3.3V         | 3.3V      | 1              |          | 1         | Alternate VCC for display                                                |
| Display I2C0 | VCC       | 1              | GPIO02   | 3         | High-driven GPIO pin in /boot/config.txt, turns display off on shutdown. |
| Display I2C0 | GND       | 2              |          | 6         |                                                                          |
| Display I2C0 | SCL       | 3              | GPIO01   | 28        |                                                                          |
| Display I2C0 | SDA       | 4              | GPIO00   | 27        |                                                                          |
| PWR\_BTN     | IN        | 1              | GPIO03   | 5         |                                                                          |
| PWR\_BTN     | OUT       | 2              |          | 6         |                                                                          |
| PWR\_LED     | IN        | 1              | GPIO17   | 11        | Pin set to high on startup in /boot/config.txt                           |
| PWR\_LED     | GND       | 2              |          | 14        |                                                                          |
| Therm        | GND       | Sleeve         |          | 14        |                                                                          |
| Therm        | DATA      | Ring           | GPIO04   | 7         | Connected to 3.3V through R1                                             |
| Therm        | VCC\_5    | Tip            |          | 4         |                                                                          |
| Buttons      | VCC\_3.3  | 2, 4, 6, 8, 10 |          | 17        |                                                                          |
| Buttons      | UP        | 1              | GPIO22   | 15        |                                                                          |
| Buttons      | DOWN      | 3              | GPIO27   | 13        |                                                                          |
| Buttons      | LEFT      | 5              | GPIO05   | 29        |                                                                          |
| Buttons      | RIGHT     | 7              | GPIO12   | 32        |                                                                          |
| Buttons      | OK        | 9              | GPIO06   | 31        |                                                                          |
| Buzzer       | GND       | 1              |          | 20        |                                                                          |
| Buzzer       | IN        | 2              | GPIO25   | 22        |                                                                          |
| Heating      | T\_VCC3.3 | 8              |          | 17        |                                                                          |
| Heating      | T\_DATA   | 7              | GPIO04   | 7         | Connected to 3.3V through R1                                             |
| Heating      | GND       | 6              |          | 34        |                                                                          |
| Heating      | VCC\_5    | 5              |          | 4         |                                                                          |
| Heating      | REL\_IN   | 4              | GPIO13   | 33        | Heating element relay                                                    |
| Heating      | OPTO\_OUT | 3              | GPIO16   | 36        | Heating element plugged in check                                         |
| Heating      | DT        | 2              | GPIO19   | 35        | Reserved for kettle scale (HX711 DT)                                     |
| Heating      | SCK       | 1              | GPIO20   | 38        | Reserved for kettle scale (HX711 SCK)                                    |
| NFC\_SPI     | SCK       | 1              | GPIO11   | 23        |                                                                          |
| NFC\_SPI     | MISO      | 2              | GPIO09   | 21        |                                                                          |
| NFC\_SPI     | MOSI      | 3              | GPIO10   | 19        |                                                                          |
| NFC\_SPI     | SS        | 4              | GPIO08   | 24        |                                                                          |
| NFC\_SPI     | VCC       | 5              |          | 17        |                                                                          |
| NFC\_SPI     | GND       | 6              |          | 39        |                                                                          |
| NFC\_SPI     | IRQ       | 7              | GPIO26   | 37        |                                                                          |
| NFC\_SPI     | RST0      | 8              | GPIO21   | 40        |                                                                          |