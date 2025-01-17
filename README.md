# Integrated Project: Autonomous Car Path Correction by Sound Commands

This project focuses on designing and implementing a system for a miniature autonomous car that responds to sound commands for redirection correction. The system uses an analog-digital audio converter to process sound signals, enabling the car to implement corrections to guided movements autonomously.

## Key Features
- **Sound Command Recognition**: A sequence of predefined sound commands is used to guide the car's movement.
- **Analog-Digital Audio Conversion**: Utilizes an ADC for processing sound signals to enable real-time response.
- **Circuit Design**: Hardware circuit designed to interface the audio processing with the car's controls.
- **Speed Regulation**: A retroactive cycle is implemented to dynamically adjust and regulate the car's speed.

## Technologies Used
- **Programming Language**: C
- **Hardware Design**: Custom circuit design for audio processing and control integration.

## Project Objectives
1. Process and interpret sound commands in real time.
2. Achieve autonomous navigation for the miniature car based on sound inputs.
3. Implement a robust speed regulation mechanism.
4. Integrate analog and digital components for seamless operation.

## How It Works
1. **Sound Command Input**: The system captures sound commands using a microphone.
2. **Signal Processing**: The analog signal is converted into a digital format using an ADC.
3. **Command Execution**: The digital command triggers predefined movement patterns (e.g., forward, backward, turn left/right).
4. **Speed Adjustment**: A retroactive feedback mechanism ensures speed is regulated based on environmental and operational constraints.

## Applications
- Demonstrates real-time audio processing and control integration.
- Explores the intersection of embedded systems, audio signal processing, and autonomous navigation.

## Future Work
- Enhance command recognition accuracy with advanced signal processing techniques.
- Optimize speed regulation for more complex terrains.
- Extend the system for additional input commands and functionalities.
