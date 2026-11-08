# Requirements Specification

**Project:** Portable Guitar Amplifier  
**Revision:** 0.2  
**Status:** Draft

## 1. Project Overview

A compact, portable, rechargeable guitar amplifier using a custom-designed PCB and an integrated loudspeaker, intended primarily for indoor bedroom practice.

## 2. Functional Requirements

REQ-001 The product should have compact dimensions to ensure portability.

REQ-002 The product shall have an integrated loudspeaker.

REQ-003 The product shall deliver at least 1 W RMS audio output power into an 8 Ω load.

REQ-004 The product shall use a loudspeaker approximately 3 inches in diameter, with a nominal impedance of 8 Ω and sensitivity of at least 85 dB SPL (1 W / 1 m).

REQ-005 The product shall operate using a rechargeable lithium-based battery, initially targeting a single-cell 3.7 V nominal battery.

REQ-006 The product shall provide clean sound with low unwanted distortion and adjustable intentional distortion.

REQ-007 The product shall include gain, volume, tone and master volume controls.

## 3. Electrical and Power Requirements

REQ-008 Battery operating time shall be at least 4 hours under defined typical-use conditions.

REQ-009 Battery charging shall use a USB-C connector with standard 5 V input, without requiring USB Power Delivery.

REQ-010 The amplifier shall support operation while connected to external USB-C power, including simultaneous battery charging and operation.

REQ-011 The amplifier shall remain operational from USB-C power when the battery is depleted, provided sufficient input power is available.

REQ-012 Target charging time shall be approximately 2–3 hours from empty to full.

REQ-013 The amplifier shall achieve THD+N below 1% when delivering 1 W RMS into an 8 Ω load in clean mode.

REQ-014 The complete amplifier and speaker system shall target a frequency response of 80 Hz–15 kHz, measured at the -3 dB points.

REQ-015 Background hiss, hum and buzzing shall not be noticeable during normal operation with no guitar connected and intentional distortion disabled.

## 4. User Interface Requirements

REQ-016 Guitar input shall use a conventional 6.35 mm TS mono jack.

REQ-017 Gain, volume, tone and master volume shall be user-adjustable.

REQ-018 The product shall include an LED power indicator.

REQ-019 A headphone output is not required.

## 5. Mechanical Requirements

REQ-020 Target dimensions shall be approximately 110 × 60 × 140 mm (W × D × H), with flexibility to increase dimensions if necessary.

REQ-021 Target weight shall be less than 0.5 kg, including the battery and speaker.

REQ-022 Portability shall be maintained as a primary design consideration.

## 6. Verification

Each requirement shall eventually have a defined verification method, such as calculation, simulation, inspection or physical measurement.

## 7. Revision History

**Revision 0.1**  
Description: Initial requirements draft.

**Revision 0.2**  
Description: Refined audio performance, speaker specifications, battery operation, charging, controls and mechanical targets.

**Revision 0.3**  
Description: Finalized audio performance targets, speaker impedance and sensitivity, clean-mode distortion, background noise, USB-C power operation, charging time and mechanical flexibility.