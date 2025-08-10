# Signal Demodulation and Noise Impact Analysis with AM, FM, and FSK Modulation

![Demodulated Signals Visualization](docs/1.png)

## Project Overview

This project simulates signal generation, noise addition, and demodulation processes for three fundamental modulation schemes:  
- **Amplitude Modulation (AM)**  
- **Frequency Modulation (FM)**  
- **Frequency Shift Keying (FSK)**  

Using Python’s **NumPy** and **Matplotlib**, it models communication signals under realistic noisy conditions, then applies demodulation techniques to recover the original data. The resulting visualizations enable qualitative assessment of demodulation effectiveness in the presence of noise.

---

## Business and Analytical Value

Signal demodulation and noise resilience analysis are critical in:  
- Designing and optimizing **wireless communication systems**  
- Enhancing **IoT sensor data transmission** reliability  
- Improving **telecommunication network performance monitoring**  
- Supporting **R&D in digital signal processing** and hardware testing  

This project provides foundational insights that assist engineers and analysts in evaluating and improving signal integrity under real-world interference.

---

## Technical Highlights

- **Signal Generation:** Binary data encoded into AM, FM, and FSK waveforms.  
- **Noise Modeling:** Additive white Gaussian noise applied with adjustable Signal-to-Noise Ratio (SNR).  
- **Demodulation Methods:**  
  - Envelope detection for AM signals  
  - Phase derivative analysis for FM  
  - Correlation-based detection for FSK  
- **Visualization:** Time-domain plots illustrate raw and demodulated signals for intuitive analysis.

---

## Tools and Technologies

- Python 3.x  
- NumPy — numerical computations and signal modeling  
- Matplotlib — data visualization  я
