---
layout: page
title: OFDMSystemSim
description: 📡 OFDM system simulation tool
full_name: mpek29/OFDMSystemSim
img: assets/img/projects/OFDMSystemSim/main.png
importance: 1
git: https://github.com/mpek29/OFDMSystemSim
github: https://github.com/mpek29/OFDMSystemSim
category: Electronics
subcategory: Signal and Image Processing
---


**OFDMSystemSim** is an open-source project designed to model and simulate an **Orthogonal Frequency Division Multiplexing (OFDM)** communication system using the **Jupyter Notebook** environment. The simulation includes transmitter and receiver chains, signal propagation over noisy and multipath channels, synchronization, and advanced analyses such as **PAPR** and **channel equalization**.

## 🎯 Purpose

- 📡 **Understand OFDM Communications**: Implement the full digital chain from symbol generation to reception.
- 🧪 **Numerical Experimentation**: Analyze the effects of noise, multipath, and timing offsets.
- 📊 **Performance Evaluation**: Compute BER, visualize spectra, histograms, and constellations.
- ⚙️ **Algorithm Exploration**: Implement oversampling, hard-clipping, synchronization techniques, etc.
- 🛠️ **Educational & Reusable**: A versatile base for signal processing students, researchers, or enthusiasts.

## 📝 Features

| 🏷️ Feature                   | 🔍 Description |
|----------------------------|----------------|
| ⚙️ **Fully Parametric Setup**   | Modulation type (QAM/PSK), SNR, number of subcarriers, symbol duration |
| 💾 **OFDM Signal Generation**   | IFFT processing, cyclic prefix insertion, signal vector construction |
| 🌊 **AWGN Channel**             | Additive white Gaussian noise based on specified SNR |
| 🛰️ **Multipath Channel**        | Impulse response modeling and convolution with variable echo amplitudes |
| 🎛️ **Timing Synchronization**   | Simulate timing offsets and evaluate simple synchronization strategies |
| 📉 **PAPR Analysis**            | CCDF evaluation and visualization of PAPR distributions |
| ✂️ **Hard Clipping**            | Reduce PAPR using nonlinear clipping with tunable thresholds |
| 📶 **Zero-Forcing Equalization**| Simple frequency-domain channel equalization |
| 📈 **Visual Outputs**           | Constellations, histograms, power spectral density, PAPR curves |

## 🖥️ Screenshots

| 📡 OFDM Signal | 📊 Histograms | 📶 Constellation |
|---------------|---------------|------------------|
| {% include image.html path="assets/img/projects/OFDMSystemSim/signal.png" width="100%" %} | {% include image.html path="assets/img/projects/OFDMSystemSim/hist.png" width="100%" %} | {% include image.html path="assets/img/projects/OFDMSystemSim/constellation.png" width="100%" %} |

## 🧪 Included Experiments

- BER vs SNR evaluation for QAM-16 and PSK-16
- Multipath channel simulation with variable echo amplitudes
- Desynchronization effects and their impact on BER and constellations
- PAPR CCDF analysis for various FFT sizes (32–1024)
- Hard clipping PAPR reduction (2 dB to 10 dB thresholds)
- Zero-forcing channel equalization

## 🛠️ Tools & Requirements

- 🧠 **Python 3.8+**
- 📦 Libraries: `numpy`, `scipy`, `matplotlib`, `notebook`
- 💻 Platform: Jupyter Notebook (local or online)

