
# Automatic Fish Food Dispenser

An automated fish-feeding project designed to dispense fish food at scheduled times using an ESP32 and a servo motor.

## Features

- Scheduled fish feeding.
- Servo-controlled food dispensing mechanism.
- Two-stage dispensing movement.
- Automatic operation based on the configured schedule.

## Hardware Components

- ESP32 development board
- Servo motor
- Fish food container with dispensing opening
- Suitable power supply

## Feeding Schedule

The dispenser is configured for two daily feeding times:

- 8:00 AM
- 8:00 PM

The actual feeding behavior depends on the uploaded firmware and its time-synchronization setup.

## Hardware Connections

See [Hardware Pinout](hardware/pinout.md) for the wiring details.

## Demonstration Video

See the video in the [`videos`](videos/) folder.

## How It Works

1. The ESP32 obtains the current time using the configured time source.
2. It checks whether a scheduled feeding time has arrived.
3. The servo moves the dispensing mechanism.
4. The mechanism returns to its resting position according to the programmed sequence.
## My Other Projects

- [Autonomous Voice-Controlled Line-Following Robot](https://github.com/tintin10jr-collab/autonomous-voice-controlled-line-following-robot)
- [Automatic Fish Food Dispenser](https://github.com/tintin10jr-collab/automatic-fish-food-dispenser-Copy)

## Future Improvements

- Reliable time synchronization after power loss.
- Prevention of duplicate feeding.
- Adjustable food portions.
- Feeding status indicators and error handling.
