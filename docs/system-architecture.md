# System Architecture

**Project:** Portable Guitar Amplifier  
**Revision:** 0.2  
**Status:** Draft

## 1. Overview

The amplifier is divided into several functional blocks. Each block performs a specific task and connects to other blocks to form the complete system.

## 2. Main Functional Blocks

1. **Guitar Input** – Receives the audio signal from the electric guitar.
2. **Pre-Amplifier** – Amplifies and conditions the input signal.
3. **Tone Control** – Adjusts the frequency response of the audio signal.
4. **Distortion Circuit** – Adds adjustable intentional distortion.
5. **Power Amplifier** – Drives the loudspeaker with the required output power.
6. **Loudspeaker** – Converts the amplified electrical signal into sound.
7. **Battery** – Two EVE INR18650-25P lithium-ion cells connected in series (2S1P), providing 7.2 V nominal and 8.4 V fully charged. Total capacity: 2500 mAh (18 Wh nominal energy).
8. **Charging Circuit** – Charges the battery through USB-C (5 V input), using a 2S-compatible charging circuit with a target charging current of 1.25 A.
9. **Battery Protection** – External 2S battery management circuit providing overcharge, over-discharge, overcurrent and short-circuit protection, with cell balancing.
10. **Power Management** – Provides and regulates the voltages required by the circuits and supports operation while the battery is charging.

## 3. Design Approach

The system architecture will be refined before selecting specific components. Each block will eventually be evaluated and designed individually.

## 4. Revision History

| Revision | Description |
|---|---|
| 0.1 | Initial system architecture draft |
| 0.2 | Defined battery configuration, cell model, capacity, charging requirements and battery protection architecture |