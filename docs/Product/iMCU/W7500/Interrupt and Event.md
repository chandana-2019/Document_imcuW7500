---
id: interrupt_and_event
title: Interrupt and Event
date: 2020-03-
---

## Content

## Introduction

W7500 contains interrupt service and event service as below

- 25 interrupt request (IRQ) lines
- One NonMaskable Interrupt(NMI)
- One event signal

## Interrupt assignments

|           |                   |                                        |                |
| --------- | ----------------- | -------------------------------------- | -------------- |
| IRQ/NMI   | Device            | Description                            | Address        |
| \-------- | \---------------- | \------------------------------------- | \------------- |
| NMI       | Watchdog timer    | Watchdog timer interrupt               | 0x0000_0008    |
| IRQ\[0\]  | SSP0              | SSP0 global interrupt                  | 0x0000_0040    |
| IRQ\[1\]  | SSP1              | SSP1 global interrupt                  | 0x0000_0044    |
| IRQ\[2\]  | UART0             | UART0 global interrupt                 | 0x0000_0048    |
| IRQ\[3\]  | UART1             | UART1 global interrupt                 | 0x0000_004C    |
| IRQ\[4\]  | UART2             | UART2 global interrupt                 | 0x0000_0050    |
| IRQ\[5\]  | I2C0              | I2C0 global interrupt                  | 0x0000_0054    |
| IRQ\[6\]  | I2C1              | I2C1 global interrupt                  | 0x0000_0058    |
| IRQ\[7\]  | GPIO0             | GPIO0 global interrupt                 | 0x0000_005c    |
| IRQ\[8\]  | GPIO1             | GPIO1 global interrupt                 | 0x0000_0060    |
| IRQ\[9\]  | GPIO2             | GPIO2 global interrupt                 | 0x0000_0064    |
| IRQ\[10\] | GPIO3             | GPIO3 global interrupt                 | 0x0000_0068    |
| IRQ\[11\] | DMA               | DMA channel 1 \~ channel 5 interrupt   | 0x0000_006C    |
| IRQ\[12\] | Dualtimer0        | Dualtimer0 global interrupt            | 0x0000_0070    |
| IRQ\[13\] | Dualtimer1        | Dualtimer1 global interrupt            | 0x0000_0074    |
| IRQ\[14\] | PWM0              | PWM0 global interrupt                  | 0x0000_0078    |
| IRQ\[15\] | PWM1              | PWM1 global interrupt                  | 0x0000_007C    |
| IRQ\[16\] | PWM2              | PWM2 global interrupt                  | 0x0000_0080    |
| IRQ\[17\] | PWM3              | PWM3 global interrupt                  | 0x0000_0084    |
| IRQ\[18\] | PWM4              | PWM4 global interrupt                  | 0x0000_0088    |
| IRQ\[19\] | PWM5              | PWM5 global interrupt                  | 0x0000_008C    |
| IRQ\[20\] | PWM6              | PWM6 global interrupt                  | 0x0000_0090    |
| IRQ\[21\] | PWM7              | PWM7 global interrupt                  | 0x0000_0094    |
| IRQ\[22\] | Reserved          |                                        | 0x0000_0098    |
| IRQ\[23\] | ADC               | ADC acquisition end interrupt          | 0x0000_009C    |
| IRQ\[24\] | TCPIP             | TCPIP global interrupt                 | 0x0000_00A0    |
| IRQ\[25\] | EXT_INT           | External pin interrupt                 | 0x0000_00A4    |
| IRQ\[26\] | Reserved          |                                        | 0x0000_00A8    |
| IRQ\[27\] | Reserved          |                                        | 0x0000_00AC    |
| IRQ\[28\] | Reserved          |                                        | 0x0000_00B0    |
| IRQ\[29\] | Reserved          |                                        | 0x0000_00B4    |
| IRQ\[30\] | Reserved          |                                        | 0x0000_00B8    |
| IRQ\[31\] | Reserved          |                                        | 0x0000_00BC    |

## Event

W7500 is able to handle internal events in order to wake up the core(WFE). The wakeup event can be generated by

- When DMA process finished