# Signal Demodulation and Noise Analysis with AM, FM, and FSK Modulation

## Overview

This project implements simulation and demodulation of communication signals with Amplitude Modulation (AM), Frequency Modulation (FM), and Frequency Shift Keying (FSK). Using Python libraries **NumPy** and **Matplotlib**, it generates modulated signals, adds noise at specified Signal-to-Noise Ratio (SNR), performs demodulation, and visualizes the results.

---

## Business & Analytical Value

Signal demodulation and noise analysis are critical in:
- **Telecommunications and wireless systems** for reliable data transmission
- **Signal processing research and development**
- **IoT device communication and sensor networks**
- **Quality assurance** in hardware and software signal processing pipelines

Understanding how noise impacts signal integrity and the effectiveness of demodulation algorithms supports improved **system design** and **fault detection**.

---

## Technical Summary

- **Signal Generation:** Synthetic binary data modulated into AM, FM, and FSK waveforms.
- **Noise Modeling:** Additive Gaussian noise based on adjustable SNR levels simulates real-world interference.
- **Demodulation Algorithms:** Envelope detection for AM, phase/frequency derivative analysis for FM, and correlation for FSK.
- **Visualization:** Time-domain plots illustrate original and demodulated signals for qualitative assessment.

---

## Tools & Technologies

- Python 3.x
- NumPy for numerical computations
- Matplotlib for data visualization
