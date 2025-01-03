
# Smoke and Gas Detection System

The Smoke and Gas Detection System is a robust IoT project designed to detect harmful smoke and gas levels in the environment. It leverages sensors and microcontroller technology to provide real-time monitoring and alert mechanisms for ensuring safety in residential and industrial settings.
![image](https://github.com/user-attachments/assets/fb67af78-c654-4c5c-a03b-78d81320770f)

---

## Features

- **Real-time Detection**: Continuously monitors for smoke and harmful gases like CO and LPG.
- **Visual Alerts**: Activates an alarm and LED notifications upon detection.
- **IoT Integration**: Capable of sending alerts to connected devices.
- **Energy Efficient**: Designed for low power consumption.
- **Customizable Thresholds**: Allows users to set gas and smoke sensitivity levels.

---

## Technologies Used

1. **Arduino Microcontroller**:
   - Central processing unit for managing sensor inputs and triggering alerts.

2. **MQ-2 Gas Sensor**:
   - Detects smoke and gases like CO, methane, and LPG.

3. **Buzzer and LED Indicators**:
   - Provides audible and visual alerts in case of detection.

4. **Breadboard and Jumper Wires**:
   - Used for prototyping the electronic connections.

5. **Power Supply**:
   - Powers the microcontroller and sensors.

---

## Hardware Requirements

- Arduino Uno or compatible microcontroller
- MQ-2 Gas Sensor
- Buzzer
- LED (Red and Green)
- Resistors (1kΩ and 330Ω)
- Breadboard
- Jumper Wires
- USB Cable for Arduino

---

## Software Requirements

- Arduino IDE
- Drivers for Arduino board (if not pre-installed)

---

## How to Set Up

1. **Hardware Connections**:
   - Connect the MQ-2 sensor's VCC, GND, and signal pin to the Arduino.
   - Attach the buzzer and LEDs to the appropriate GPIO pins of the Arduino.
   - Refer to the circuit diagram provided in the repository for precise connections.

2. **Software Installation**:
   - Install the [Arduino IDE](https://www.arduino.cc/en/software).
   - Open the Arduino IDE and configure the board settings (select the correct board and COM port).

3. **Uploading the Code**:
   - Navigate to the `/code` directory of this repository.
   - Open the `.ino` file in Arduino IDE.
   - Verify and upload the code to the Arduino board.

4. **Testing the System**:
   - Power the Arduino board.
   - Expose the MQ-2 sensor to smoke or gas to test detection.
   - Observe the buzzer and LED behavior for alerts.

---

## Circuit Diagram

Refer to the `circuit_diagram.jpg` file in the repository for the complete wiring layout.

---

## Repository Structure

```plaintext
smoke-gas-detector-main/
├── README.md              # Project overview
├── circuit_diagram.jpg    # Circuit diagram for hardware setup
├── code/                  # Arduino source code
│   └── smoke_gas_detector.ino
├── images/                # Additional project images
└── LICENSE                # License information
```

---

## Contribution

Contributions to this project are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Added feature"`).
4. Push the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

Special thanks to the open-source community for tools and resources that made this project possible.

