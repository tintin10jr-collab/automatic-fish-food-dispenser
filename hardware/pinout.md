
# Hardware Connections

## Components
- ESP32 development board
- Servo motor
- Fish food container and dispensing mechanism

## Pin Connections

| Servo Wire | ESP32 Connection |
|---|---|
| Signal (orange/yellow) | GPIO18, if used in the current code |
| VCC (red) | Appropriate rated power supply |
| GND (brown/black) | Ground |

## Power and Safety
- Check the servo's voltage and current requirements.
- Do not power a high-current servo directly from an ESP32 GPIO pin.
- If using a separate servo supply, connect its ground to ESP32 ground.
- Confirm the wiring against the actual hardware before powering on.
