# Gas-Leakage-Detection-8051
This project detects gas leaks using the MQ-2 gas sensor and an AT89C51 microcontroller. When a gas leak is detected, the system activates a buzzer/LED and displays a warning on an LCD screen.

---

### 🔧 Components
- AT89C51 Microcontroller
- MQ-2 Gas Sensor
- 16x2 LCD Display (LM016L)
- LED / Buzzer
- Crystal Oscillator (11.0592 MHz)
- Capacitors (33µF, 10µF)
- Resistor (10k, 220Ω)
- Push Button (Reset)
- Proteus 8 Simulator
- Keil µVision

## 🔍 Working Principle
- The MQ-2 Gas Sensor detects gases like LPG, propane, methane, etc. It gives:
- Analog output based on concentration.
- Digital output (HIGH when gas is above threshold).
- The AT89C51 microcontroller reads this digital output.
- If gas is detected (sensor output = 1), it:
- Turns ON an LED.
- Displays "Gas Detected" on the LCD.
- If no gas is detected (sensor output = 0), it:
- Keeps LED OFF.
- Displays "Safe" on the LCD.

## 📄 Applications
- Home kitchens
- Gas-powered factories
- Restaurants
- Laboratories
- Fuel storage areas


