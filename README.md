# Fiber Optic Voice Communication System

## Overview

This project consisted of the assembly and analysis of the FO-30K Fiber Optics Kit. The objective was to demonstrate the application of optical fiber communication for the transmission of audio signals.

The system uses a transmitter circuit to convert an electrical signal from a microphone into a light signal through an LED. The signal is transmitted through a fiber optic cable to a phototransistor receiver, where it is converted back into an electrical signal, amplified, and reproduced as audio through a speaker.

## How It Works

The input to the system is the voice signal that is picked up by the microphone which has a 9 V battery as its power source. The voltage produced by the microphone will modulate the current that flows to the transmitting LED whose intensity depends upon the tone of voice and its volume.

The light from the transmitting LED propagates through the fiber optic cable to the phototransistor where it is converted into a current in a common collector configuration. The current produced at the phototransistor is directly proportional to the intensity of the input light at its base.

The resulting current is then converted into an electrical signal that is further amplified by the LM386 audio amplifier and then passed on to the speaker where it is played as the output of the system.

### System Block Diagram

![Fiber Optic Voice Communication System Block Diagram](fiber%20optic%20block%20diagram.jpg)

## Key Components

- FO-30K Fiber Optics Kit
- Microphone
- 2N3904 transistor
- LED transmitter
- Fiber optic cable
- Phototransistor receiver
- LM386 audio amplifier
- Speaker
- 9 V power supply

## Testing & Analysis

The transmitter and receiver circuits were tested using measurement equipment to observe circuit operation and analyze the signals throughout the system.

### Op-Amp Measurements

**Op-amp Inverting Input**

![Op-amp Inverting Input](Op-amp%20Inverting%20Input.jpeg)

**Op-amp Non-inverting Input**

![Op-amp Non-inverting Input](Op-amp%20Non-inverting%20Input.jpeg)

**Op-amp Output — Microphone Off**

![Op-amp Output Mic Off](Op-amp%20Output%20Mic%20Off.jpeg)

**Op-amp Output — Microphone On**

![Op-amp Output Mic On](Op-amp%20Output%20Mic%20On.jpeg)
