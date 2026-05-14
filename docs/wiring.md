# Wiring Guide

## Recommended Wiring

| LD2410C | ESP32 |
|---|---|
| VCC | 5V |
| GND | GND |
| TX | GPIO16 |
| RX | GPIO17 |

## Important

- TX and RX are crossed
- Use ESP32 hardware UART
- Use stable 5V power
- Avoid metal enclosures


![LD2410C Wiring Diagram](docs/images/wiring-diagram.png)
