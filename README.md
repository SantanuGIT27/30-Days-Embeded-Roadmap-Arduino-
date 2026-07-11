# 30-Day Embedded Systems Challenge — Arduino Uno + Tinkercad

![Days Completed](https://img.shields.io/badge/Days%20Completed-0%2F30-blue)
![Platform](https://img.shields.io/badge/Platform-Tinkercad-orange)
![Language](https://img.shields.io/badge/Language-C%2FC%2B%2B-yellow)

## About

Starting from zero electronics/embedded systems knowledge, I set myself a 30-day challenge: build one Arduino Uno project every day using Tinkercad's circuit simulator, and document the entire journey — code, wiring, and a working demo — for every single build.

This repo is the code + wiring + demo archive for that challenge. I'm also posting daily progress on LinkedIn — link below.

**Update the badge above as you go** — e.g. after Day 12, change it to `12%2F30`.

## Tools & Tech

- **Arduino Uno R3** (simulated)
- **Tinkercad Circuits** — browser-based circuit simulator
- **Arduino C/C++**
- Libraries used across the month: `Servo.h`, `DHT.h`, `LiquidCrystal.h`, `Keypad.h`, `IRremote.hpp`

## Repo Structure

Each day has its own folder containing the code, a wiring screenshot, and a link to the demo video/GIF.

```
day01-led-blink/
├── code.ino
├── wiring-screenshot.png
└── demo.md   (contains a link to the demo video/GIF)
```

## Day-by-Day Log

| Day | Project | Concept Learned | Code | Demo |
|---|---|---|---|---|
| 1 | LED Blink | `pinMode`, `digitalWrite` | [code](day01-led-blink/code.ino) | [demo](day01-led-blink/demo.md) |
| 2 | LED Chase Pattern | Arrays, `for` loops | [code](day02-led-chase/code.ino) | [demo](day02-led-chase/demo.md) |
| 3 | Pushbutton Input | Digital read, pull-down resistors | [code](day03-pushbutton/code.ino) | [demo](day03-pushbutton/demo.md) |
| 4 | Button Debouncing | `millis()`, signal noise | [code](day04-debounce/code.ino) | [demo](day04-debounce/demo.md) |
| 5 | Buzzer + tone() | Frequency-based sound output | [code](day05-buzzer/code.ino) | [demo](day05-buzzer/demo.md) |
| 6 | Potentiometer + LED Brightness | `analogRead`, PWM, `map()` | [code](day06-potentiometer/code.ino) | [demo](day06-potentiometer/demo.md) |
| 7 | **Weekly Recap #1** | — | — | [LinkedIn post](#) |
| 8 | LDR Auto Night Light | Voltage dividers, analog sensing | [code](day08-ldr/code.ino) | [demo](day08-ldr/demo.md) |
| 9 | PIR Motion Sensor + LED | Motion detection | [code](day09-pir/code.ino) | [demo](day09-pir/demo.md) |
| 10 | PIR + Buzzer Mini Alarm | Reusable sensor logic | [code](day10-pir-alarm/code.ino) | [demo](day10-pir-alarm/demo.md) |
| 11 | Ultrasonic Distance Sensor | `pulseIn()`, sound-based measurement | [code](day11-ultrasonic/code.ino) | [demo](day11-ultrasonic/demo.md) |
| 12 | Ultrasonic Parking Sensor | Tiered threshold logic | [code](day12-parking-sensor/code.ino) | [demo](day12-parking-sensor/demo.md) |
| 13 | DHT22 Temp/Humidity Sensor | External libraries | [code](day13-dht22/code.ino) | [demo](day13-dht22/demo.md) |
| 14 | **Weekly Recap #2** | — | — | [LinkedIn post](#) |
| 15 | Servo Motor Sweep | `Servo.h`, angle control | [code](day15-servo-sweep/code.ino) | [demo](day15-servo-sweep/demo.md) |
| 16 | Servo + Potentiometer | Analog input → physical output | [code](day16-servo-pot/code.ino) | [demo](day16-servo-pot/demo.md) |
| 17 | RGB LED Color Mixing | PWM, `analogWrite` | [code](day17-rgb-led/code.ino) | [demo](day17-rgb-led/demo.md) |
| 18 | DC Motor + Transistor Driver | Transistors, flyback diodes | [code](day18-dc-motor/code.ino) | [demo](day18-dc-motor/demo.md) |
| 19 | 16x2 LCD "Hello World" | `LiquidCrystal.h`, contrast tuning | [code](day19-lcd-hello-world/code.ino) | [demo](day19-lcd-hello-world/demo.md) |
| 20 | LCD + DHT22 Live Readout | Combining sensor + display | [code](day20-lcd-dht22/code.ino) | [demo](day20-lcd-dht22/demo.md) |
| 21 | **Weekly Recap #3** | — | — | [LinkedIn post](#) |
| 22 | 7-Segment Display | Manual segment mapping | [code](day22-7segment/code.ino) | [demo](day22-7segment/demo.md) |
| 23 | IR Receiver + Remote Decode | `IRremote.hpp`, signal decoding | [code](day23-ir-remote/code.ino) | [demo](day23-ir-remote/demo.md) |
| 24 | Joystick Module | Dual potentiometers + button | [code](day24-joystick/code.ino) | [demo](day24-joystick/demo.md) |
| 25 | 4x4 Keypad Basics | `Keypad.h`, row/column scanning | [code](day25-keypad/code.ino) | [demo](day25-keypad/demo.md) |
| 26 | Keypad + LCD Access Control | String handling, integration | [code](day26-keypad-lcd/code.ino) | [demo](day26-keypad-lcd/demo.md) |
| 27 | Capstone: Weather Station (Start) | Combining sensor + display + alerts | [code](day27-29-capstone-weather-station/code.ino) | [demo](day27-29-capstone-weather-station/demo.md) |
| 28 | **Weekly Recap #4** + Capstone Progress | — | — | [LinkedIn post](#) |
| 29 | Capstone: Weather Station (Final) | Full working demo | [code](day27-29-capstone-weather-station/code.ino) | [demo](day27-29-capstone-weather-station/demo.md) |
| 30 | **Grand Recap** | Full 30-day reflection | — | [LinkedIn post](#) |

*Replace the `#` links above with your actual LinkedIn post URLs as you publish each day.*

## 🌟 Featured Project: Weather Station (Capstone)

The final project of the challenge — combines everything learned across the month into one working system.

- **Sensor:** DHT22 (temperature + humidity)
- **Display:** 16x2 LCD, live readout updated every 2 seconds
- **Alerts:** LED + buzzer trigger when temperature goes outside a safe range

📁 [View code & wiring](day27-29-capstone-weather-station/) · 🎥 [Watch demo](day27-29-capstone-weather-station/demo.md)

## What I Learned

- Sensors rarely "just work" out of the box — most need supporting circuitry (voltage dividers, pull-up resistors) or a library to produce a usable value.
- Code is only half of embedded systems — the other half is genuinely electrical (transistor drivers, flyback diodes, contrast tuning, debouncing).
- Most "impressive" projects aren't built from new concepts — they're combinations of simpler things learned earlier (e.g., the keypad + LCD access control reuses Week 1's string handling and Week 3's display logic).
- Interrupts, timers, and low-level hardware control (coming up in the STM32 phase) are the next layer beneath what Arduino's simplified functions abstract away.

## What's Next

Continuing this challenge into a second phase: **30 Days of STM32 (via Wokwi)** — moving from Arduino's simplified API into real ARM Cortex microcontrollers, HAL-level code, interrupts, timers, and an intro to FreeRTOS. That log will live in a separate repo, linked here once it starts.

## Connect

Following along daily on LinkedIn: **[add your LinkedIn profile/post link here]**

Feel free to fork this repo if you want to run the same challenge yourself — happy to answer questions via Issues.

## License

This project is licensed under the [MIT License](LICENSE) — feel free to reuse any code here for your own learning.
