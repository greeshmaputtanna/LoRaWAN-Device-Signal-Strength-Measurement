# LoRaWAN-Device-Signal-Strength-Measurement


This project focuses on measuring the received power of a LoRaWAN device using GQRX and comparing antenna performance. The goal is to evaluate the average signal strength at various distances using different antennas.

## Project Overview

LoRaWAN, which stands for Long-Range Wide Area Network, is a wireless communication protocol and technology designed for the Internet of Things (IoT) and low-power, wide-area network (LPWAN) applications. It provides long-range wireless connectivity for devices with minimal energy consumption, making it ideal for various IoT applications.

In this project, we aim to measure the received power of a LoRaWAN device and compare antenna performance based on the signal strength at different distances.

## Instructions

### Step 1: Capture the Spectrum with GQRX
1. Launch **GQRX** and capture the spectrum of the LoRaWAN device.
2. Set the receiver gain **manually** (Do **not** use AGC).
3. Use the **telescopic antenna** for the initial capture.
4. Take a screenshot of the received spectrum.
5. Identify and note the **average signal strength** from the spectrum.

### Step 2: Antenna Comparison
1. Replace the telescopic antenna with a **different antenna**.
2. Capture the spectrum again.
3. Compare the new spectrum with the one from the telescopic antenna.
4. Take a screenshot of the new spectrum.

### Step 3: Signal Strength Measurement at Different Distances
1. Using the **best-performing antenna**, measure the average signal strength at **5 different distances**.
2. Record the average signal strength at each distance.

### Step 4: Plotting the Results
1. Use a plotting tool (e.g., **MATLAB**, Python) to plot the trendline of the measured signal strengths across different distances.
2. Analyze the trend and evaluate how distance affects the received signal strength.

## Requirements
- **GQRX** software installed and configured.
- **LoRaWAN device** for signal measurement.
- Two different **antennas** for performance comparison.
- Tool for **signal plotting** (MATLAB, Python, etc.).

## Deliverables
- Screenshots of the spectrum from GQRX for each antenna.
- A plot showing the trendline of signal strength at 5 different distances.
- Analysis of the antenna performance and signal strength behavior over distance.
