# LD2410C ESPHome Presence Sensor

DIY mmWave human presence sensor using:

- ESP32
- Hi-Link LD2410C
- ESPHome
- Home Assistant

This project provides:

- Human presence detection
- Still person detection
- Motion detection
- Distance tracking
- Room occupancy automations
- Full ESPHome YAML examples
- Tuning guide
- Home Assistant integration

---

## Features

- Reliable mmWave presence sensing
- Detects sitting humans unlike PIR sensors
- Home Assistant native integration
- Wi-Fi based ESPHome firmware
- OTA updates
- Configurable sensitivity gates
- Engineering mode support
- Optional Bluetooth configuration

---

## Hardware

| Part | Description |
|---|---|
| ESP32 | Main controller |
| LD2410C | mmWave radar sensor |
| USB power supply | 5V stable supply |
| Plastic enclosure | Optional |

---

## Wiring

| LD2410C | ESP32 |
|---|---|
| VCC | 5V |
| GND | GND |
| TX | GPIO16 |
| RX | GPIO17 |

---

## Documentation

- [Wiring Guide](docs/wiring.md)
- [Tuning Guide](docs/tuning.md)
- [Troubleshooting](docs/troubleshooting.md)

---

## License

MIT License
