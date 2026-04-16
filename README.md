# LiFi Project using Arduino

This project implements a **Light Fidelity (LiFi)** communication system. It uses visible light to transmit data between two Arduino boards, offering a high-speed, secure alternative to traditional Wi-Fi.

## 🚀 Features
- **Wireless Data Transmission:** Transmits text/data via LED light.
- **Real-time Communication:** Low latency transmission using Arduino's digital I/O.
- **Secure:** Light cannot pass through walls, making the connection inherently more secure than RF.
- **Cost-Effective:** Built using standard off-the-shelf electronic components.

## 🛠 Hardware Components
- 2x Arduino Uno (or Nano)
- 1x High-power White LED (Transmitter)
- 1x LDR (Light Dependent Resistor) or Solar Panel (Receiver)
- 1x NPN Transistor (e.g., BC547 for driving the LED)
- Resistors (220Ω, 10kΩ)
- Breadboard and Jumper Wires

## 📊 How It Works
1. **Transmitter:** The Arduino converts digital data into a series of rapid light pulses (On/Off) via the LED.
2. **Medium:** The data travels through the air as light waves.
3. **Receiver:** An LDR or Solar Cell detects the light intensity changes and converts them back into electrical signals, which the second Arduino decodes into the original message.

## 🔧 Circuit Diagram
[Add an image or a link to your circuit diagram here]

## 💻 Software Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/srisanthosh609/LiFi-project-using-Arduino.git](https://github.com/srisanthosh609/LiFi-project-using-Arduino.git)
