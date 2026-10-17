
# Hardware Pin Diagram

## ESP32 to Servo Motor

| Servo Wire | ESP32 / Power Connection |
|---|---|
| Orange / Yellow (Signal) | GPIO18 |
| Red (VCC) | Servo power supply positive |
| Brown / Black (GND) | Common GND |

## Wiring Diagram

```text
ESP32                  Servo
-----                  -----
GPIO18 --------------> Signal

External supply (+) -> VCC
External supply (-) --+-> GND
ESP32 GND ------------+
```

## Important Notes
- GPIO18 controls the servo; it does not power it.
- Use a supply rated for the servo.
- Connect ESP32 GND and servo supply GND together.
- Verify the wiring before applying power.
