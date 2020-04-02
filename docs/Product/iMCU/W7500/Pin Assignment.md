---
id: pin_assignment
title: Pin Assignment
date: 2020-03-
---

## Content

## Pin Layout

### W7500 Pin Layout

![W7500 Pin Layout](http://wizwiki.net/wiki/lib/exe/fetch.php?media=products:w7500:overview:pin_layout.png)

## Pin Description

|     |          |      |               |          |             |           |
| --- | -------- | ---- | ------------- | -------- | ----------- | --------- |
|     |          |      | Description   |          |             |           |
| Pin | Symbol   | Type | Main          | 2nd      | 3rd         | 4th       |
| 1   | PC_08    | AIO  | PWM0 / CAP0   | GPIO3_8  | SCL0        | AIN7      |
| 2   | PC_09    | AIO  | PWM1 / CAP1   | GPIO3_9  | SDA0        | AIN6      |
| 3   | PC_10    | AIO  | U_TXD2        | GPIO3_10 | PWM2 / CAP2 | AIN5      |
| 4   | PC_11    | AIO  | U_RXD2        | GPIO3_11 | PWM3 / CAP3 | AIN4      |
| 5   | PC_12    | AIO  | AIN3          | GPIO3_12 | SSEL0       | AIN3      |
| 6   | PC_13    | AIO  | AIN2          | GPIO3_13 | SCLK0       | AIN2      |
| 7   | PC_14    | AIO  | AIN1          | GPIO3_14 | MISO0       | AIN1      |
| 8   | PC_15    | AIO  | AIN0          | GPIO3_15 | MOSI0       | AIN0      |
| 9   | GND      | GND  | Ground        |          |             |           |
| 10  | VDD      | PWR  | VDD           |          |             |           |
| 11  | PD_00    | IO   | CRS/TXD3      | GPIO4_0  |             |           |
| 12  | PD_01    | IO   | RXDV/TXD2     | GPIO4_1  |             |           |
| 13  | PD_02    | IO   | RXD0/TXD1     | GPIO4_2  |             |           |
| 14  | PD_03    | IO   | RXD1/TXD0     | GPIO4_3  |             |           |
| 15  | PD_04    | IO   | RXD2/TXCLK    | GPIO4_4  |             |           |
| 16  | PB_06    | IO   | RXD3/DUP      | GPIO2_6  |             |           |
| 17  | PB_07    | IO   | RXCLK/RXCLK   | GPIO2_7  |             |           |
| 18  | PB_08    | IO   | DUP/RXD3      | GPIO2_8  |             |           |
| 19  | PB_09    | IO   | TXCLK/RXD2    | GPIO2_9  |             |           |
| 20  | PB_10    | IO   | TXD0/RXD1     | GPIO2_10 |             |           |
| 21  | PB_11    | IO   | TXD1/RXD0     | GPIO2_11 |             |           |
| 22  | PB_12    | IO   | TXD2/RXDV     | GPIO2_12 |             |           |
| 23  | PB_13    | IO   | TXD3/CRS      | GPIO2_13 |             |           |
| 24  | PB_04    | IO   | TXEN          | GPIO2_04 |             |           |
| 25  | PB_05    | IO   | COL           | GPIO2_05 |             |           |
| 26  | PB_14    | IO   | MDIO/MDC      | GPIO2_14 |             |           |
| 27  | PB_15    | IO   | MDC/MDIO      | GPIO2_15 |             |           |
| 28  | RSTn     | I    | RSTn          |          |             |           |
| 29  | PA_00    | IO   | GPIO1_0       | GPIO1_0  | PWM6/CAP6   |           |
| 30  | PA_01    | IO   | TXD0/RXD1     | GPIO1_1  | PWM7/CAP7   |           |
| 31  | PA_02    | IO   | GPIO1_2       | GPIO1_2  | CLKOUT      |           |
| 32  | TEST     | GND  | Ground        |          |             |           |
| 33  | PA_05    | IO   | SSEL0         | GPIO1_5  | SCL1        | PWM2/CAP2 |
| 34  | PA_06    | IO   | SCLK0         | GPIO1_6  | SDA1        | PWM3/CAP3 |
| 35  | PA_07    | IO   | MISO0         | GPIO1_7  | U_CTS1      | PWM4/CAP4 |
| 36  | PA_08    | IO   | MOSI0         | GPIO1_8  | U_RTS1      | PWM5/CAP5 |
| 37  | PA_09    | IO   | SCL0          | GPIO1_9  | U_TXD1      | PWM6/CAP6 |
| 38  | PA_10    | IO   | SDA0          | GPIO1_10 | U_RXD1      | PWM7/CAP7 |
| 39  | BOOT     | IO   | BOOT          |          |             |           |
| 40  | PA_11    | IO   | U_CTS0        | GPIO1_11 | SSEL1       |           |
| 41  | PA_12    | IO   | U_RTS0        | GPIO1_12 | SCLK1       |           |
| 42  | PA_13    | IO   | U_TXD0        | GPIO1_13 | MISO1       |           |
| 43  | PA_14    | IO   | U_RXD0        | GPIO1_14 | MOSI1       |           |
| 44  | PA_15    | IO   | GPIO1_15      | GPIO1_15 |             |           |
| 45  | PB_00    | IO   | SSEL1         | GPIO2_0  | U_CTS0      |           |
| 46  | PB_01    | IO   | SCLK1         | GPIO2_1  | U_RTS0      |           |
| 47  | PB_02    | IO   | MISO1         | GPIO2_2  | U_TXD0      |           |
| 48  | PB_03    | IO   | MOSI1         | GPIO2_3  | U_RXD0      |           |
| 49  | PA_03    | IO   | SWCLK         | GPIO1_3  |             | PWM0/CAP0 |
| 50  | PA_04    | IO   | SWDIO         | GPIO1_4  |             | PWM1/CAP1 |
| 51  | PC_06    | IO   | GPIO3_6       | GPIO3_6  | U_TXD2      |           |
| 52  | PC_07    | IO   | GPIO3_7       | GPIO3_7  | U_RXD2      |           |
| 53  | PC_00    | IO   | U_CTS1        | GPIO3_0  | PWM0/CAP0   |           |
| 54  | PC_01    | IO   | U_RTS1        | GPIO3_1  | PWM1/CAP1   |           |
| 55  | PC_02    | IO   | U_TXD1        | GPIO3_2  | PWM2/CAP2   |           |
| 56  | PC_03    | IO   | U_RXD1        | GPIO3_3  | PWM3/CAP3   |           |
| 57  | PC_04    | IO   | SCL1          | GPIO3_4  | PWM4/CAP4   |           |
| 58  | PC_05    | IO   | SDA1          | GPIO3_5  | PWM5/CAP5   |           |
| 59  | GND      | GND  | Ground        |          |             |           |
| 60  | NC       | NC   | Not Connected |          |             |           |
| 61  | VDD      | PWR  | VDD           |          |             |           |
| 62  | GND      | GND  | Ground        |          |             |           |
| 63  | XTAL_IN  | I    | Xtal in       |          |             |           |
| 64  | XTAL_OUT | O    | Xtal out      |          |             |           |

---
