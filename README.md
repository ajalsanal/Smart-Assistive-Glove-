# Smart Assistive Glove

## Overview 🚀
The **Smart Assistive Glove** is an Arduino-based project designed to help individuals with speech impairments communicate effectively. It uses push buttons embedded in a glove to send predefined messages to an LCD display while also triggering a buzzer and LED at the receiver end. The communication between the glove and the receiver is achieved using an RF transmitter and receiver, with an option to integrate the HC-05 Bluetooth module.

## Features 🔥
- **Push Button Activation:** Each button corresponds to a specific message.
- **LCD Display:** Displays predefined messages when a button is pressed.
- **Wireless Communication:** Uses RF transmitter and receiver (or optionally Bluetooth).
- **Audio-Visual Feedback:** Buzzer and LED activate at the receiver end.
- **Arduino-Based:** Built using an Arduino Uno for both transmitter and receiver.

## Components Used 🛠️
- Arduino Uno (2x)
- Push Buttons
- 16x2 LCD Display with I2C Module
- RF Transmitter and Receiver Modules
- Buzzer
- LED
- Power Supply (Battery or USB)
- (Optional) HC-05 Bluetooth Module

## Circuit Design ⚡
### Transmitter Side:
- Push buttons are connected to Arduino digital input pins.
- Each button press sends a signal via the RF transmitter.
- LCD displays the corresponding message.

### Receiver Side:
- RF receiver receives signals from the transmitter.
- Corresponding LED and buzzer activate based on the received signal.
- Can be modified to work with an HC-05 Bluetooth module.

## Setup and Installation 🏗️
1. **Assemble the Circuit:** Connect all components as per the circuit diagram.
2. **Upload the Code:** Use the Arduino IDE to upload the respective transmitter and receiver codes.
3. **Power Up the Devices:** Ensure both transmitter and receiver are powered correctly.
4. **Test the System:** Press buttons to check if the LCD, buzzer, and LED function as expected.

## Future Enhancements 🚀
- Integrate Bluetooth for wider range communication.
- Add more gestures using flex sensors.
- Implement voice output for messages.

## Contributing 🤝
Feel free to contribute by improving the code, circuit design, or adding new features. Fork the repository and submit a pull request with your changes.

--
