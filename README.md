# 🎧 Audio Frequency Analysis Using Analog Circuits

<div align="center">

## 🏆 1st Prize Winner – Hack Genesis 2026
### 24-Hour National Level Hardware Hackathon

**Team: Circuit Crafters**

*KLE Technological University, Dr. M. S. Sheshgiri Campus, Belagavi*

---

**Built with Analog Electronics • ESP32 • Signal Processing**

</div>

---

# 📖 Project Overview

This project was developed during **Hack Genesis 2026**, a 24-hour National Level Hardware Hackathon.

The objective was to design and implement an **Audio Frequency Analysis System** capable of accurately acquiring, conditioning, and processing real-world microphone signals using analog circuitry before performing digital frequency analysis using an ESP32.

Unlike software-only implementations, this project focused heavily on **analog signal conditioning**, requiring careful circuit design to amplify weak microphone signals, eliminate unwanted frequencies, shift voltage levels, and interface reliably with an ADC.

The project was awarded **🥇 First Prize in the Hardware Track**.

---

# 🎯 Problem Statement

Design an Analog Audio Frequency Analysis System capable of

- Capturing microphone signals
- Amplifying low-level analog signals
- Removing unwanted frequencies
- Providing adjustable gain
- Converting bipolar analog signals into ADC-compatible levels
- Performing digital frequency analysis using ESP32

---

# 🚀 Objectives

- Design a low-noise analog front end
- Implement variable gain amplification
- Design active High Pass and Low Pass Filters
- Perform DC Level Shifting
- Interface analog output with ESP32 ADC
- Display accurate audio frequency information

---

# 🏗️ System Architecture

```text
Microphone
     │
     ▼
Pre-Amplifier
     │
     ▼
Variable Gain Amplifier
     │
     ▼
High Pass Filter
     │
     ▼
Low Pass Filter
     │
     ▼
Level Shifter
     │
     ▼
ESP32 ADC
     │
     ▼
Digital Frequency Analysis
```

---

# ⚙️ Hardware Used

- ESP32 Development Board
- Electret Microphone
- OP07 Operational Amplifier
- Passive Components
- Potentiometer
- Breadboard
- Oscilloscope
- Function Generator

---

# 💻 Software Used

- LTSpice
- Proteus
- Arduino IDE

---

# 🔬 Working Principle

The microphone captures the incoming audio signal, which is initially very weak.

The signal is amplified using a low-noise analog preamplifier.

A variable gain stage allows adjustment for different signal amplitudes.

The signal then passes through active High Pass and Low Pass filters to retain the desired frequency band while suppressing unwanted noise.

Since the ESP32 ADC accepts only positive voltages, the conditioned analog signal is shifted using a DC level shifter.

Finally, the ESP32 samples the signal and performs digital frequency analysis.

---

# 📊 Features

✔ Analog Signal Conditioning

✔ Variable Gain Amplifier

✔ Active HPF

✔ Active LPF

✔ Level Shifting

✔ ESP32 ADC Interface


---

# 📂 Repository Structure

```
docs/
hardware/
simulation/
firmware/
images/
README.md
```

---

# 🏆 Achievement

🥇 **1st Prize**

**Hack Genesis 2026**

24-Hour National Level Hardware Hackathon

KLE Technological University

Dr. M. S. Sheshgiri Campus, Belagavi

---

# 👨‍💻 Team Members

- Shridhar Angadi
- Shrinivas M
- Vaibhav Revankar
- Vanishree Kulakarni

---

# 🚀 Future Scope

- Automatic Gain Control (AGC)
- FFT-based Spectral Analysis
- OLED Display Integration
- PCB Implementation
- MEMS Microphone Interface
- DSP Optimization
- Audio Classification
- Edge AI Integration

---

# 📸 Project Gallery

Images of the prototype, circuit, simulations, implementation, and hackathon journey will be added here.

---

# 🙏 Acknowledgement

We sincerely thank the organizers, mentors, judges, IEEE Student Branch, NKSSS, and KLE Technological University, Dr. M. S. Sheshgiri Campus, Belagavi, for providing us with this opportunity to learn, innovate, and compete.

---

## ⭐ If you found this project interesting, consider giving it a Star.
