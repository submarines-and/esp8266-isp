Use esp8266 to program an attiny85. From this [tutorial](https://www.youtube.com/watch?v=tBq3sO1Z-7o&list=PLNyfXcjhOAwOF-7S-ZoW2wuQ6Y-4hfjMR&index=2), but for esp instead of an atmega/arduino. Last video uses a attiny.

# Wiring

| Esp8266    | Attiny86 |
| -------- | ------- |
| SCK (D5)  | pin 7 (SCK)     |
| MISO (D6) | pin 6 (MISO)      |
| MOSI (D7)    | pin 5 (MOSI)     |
| D4    | pin 1 (RESET)     |
| GND    | pin 4     |
| 3.3v     | pin 8    |

Also 10kohm pull-up resistor from attiny pin1 to power rail


![Wires](./image.jpeg)