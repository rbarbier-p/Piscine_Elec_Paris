
## BOM

| Manufacture Part Number | Manufacturer               | Package      | Description                      | Quantity |
| ----------------------- | -------------------------- | ------------ | -------------------------------- | -------- |
| ATMEGA328P-AU           | MICROCHIP                  | TQFP-32(7x7) | AVR Microcontroller - ATmega328p | 1        |
| X322516MLB4SI           | YXC Crystal Oscillators    | SMD3225-4P   | Crystal Oscillator - 16MHz 9pF   | 1        |
| B3U-1000P               | OMRON                      | SMD,3x2.5mm  | Round Button - 2.5mm 12V         | 1        |
| TZ-P2-0603YGTCS1-0.6T   | TUOZHAN                    | 0603         | Indication LED - Green 1.9V~2.4V | 1        |
| XL-1608SURC-06          | XINGLIGHT                  | 0603         | Indication LED - Red 2.3V        | 1        |
| CL10A105KB8NNNC         | Samsung Electro-Mechanics  | 0603         | Ceramic Capacitor - 1uF 50V      | 1        |
| CC0603KRX7R9BB104       | YAGEO                      | 0603         | Ceramic Capacitor - 100nF 50V    | 3        |
| CL10C120JB8NNNC         | Samsung Electro-Mechanics  | 0603         | Ceramic Capacitor - 12pF 50V     | 2        |
| RC0603FR-0710KL         | YAGEO                      | 0603         | Chip Resistor - 10kΩ 75V         | 2        |
| 0603WAF3300T5E          | UNI-ROYAL                  | 0603         | Chip Resistor - 330Ω 75V         | 1        |

<br>

## Pinout Description

<pre>
      _⎽⎽⎽⎽⎽⎽⎽⎽⎽_⎽_⎽_
   30|○                  ○|1
   29|○                  ○|2
   28|○                  ○|3
   27|○                  ○|4
   26|○                  ○|5
   25|○                  ○|6
   24|○                  ○|7
   23|○                  ○|8
   22|○                  ○|9
   21|○                  ○|10
   20|○                  ○|11
   19|○ ◻  ○  ○  ○  ○  ○ ○|12
      ⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺⎺
       18 17 16 15 14 13
  
</pre>


| Board Pin | Pin type | ATmega328p Pin |
| :-: | :-: | :-: |
| 1 | D9 | PB1 | D4 / PD4 | D3 / PD3 | D2 / PD2 | GND | RST  | RXI  | TXO |
| 2 | D8 | PB0 | | GND | RST | VCC | A3  | A2  | A1  | A0  | SCK | MISO | MOSI | D10 |
| 3 | D7 | PD7 | | RXI | VCC | GND | GND |     |     |     |      |      |     |
| 4 | D6 | PD6 |
| 5 | D5 | PD5 |
| 6 | D4 | PD4 |
| 7 | D3 | PD3 |
| 8 | D2 | PD2 |
| 9 | GND | - |
| 10 | RST | R̅E̅S̅E̅T̅/PC6
| 11 | RXI | PD0
| 12 | TXO | PD1
| 13 | GND | -
| 14 | GND | -
| 15 | VCC | -
| 16 | RXI | PD0
| 17 | TXO | PD1
| 18 | DTR | R̅E̅S̅E̅T̅/PC6
| 19 | RAW | -
| 20 | GND | -
| 21 | RST | R̅E̅S̅E̅T̅/PC6
| 22 | VCC | - 
| 23 | A3 | PC3
| 24 | A2 | PC2
| 25 | A1 | PC1
| 26 | A0 | PC0
| 27 | SCK | PB5
| 28 | MISO | PB4
| 29 | MOSI |PB3
| 30 | D10 | PB2

