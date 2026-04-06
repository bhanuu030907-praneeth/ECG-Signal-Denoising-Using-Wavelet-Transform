ECG Signal Denoising using Discrete Wavelet Transform (DWT)

This project implements ECG signal denoising using Discrete Wavelet Transform (DWT) in Python. The objective is to remove noise such as baseline drift, power line interference, and EMG noise from ECG signals while preserving important features.

## Overview
Electrocardiogram (ECG) signals are often corrupted by different types of noise during acquisition. This project uses wavelet decomposition and thresholding techniques to effectively denoise the ECG signal.

## Features
- Synthetic ECG signal generation
- Addition of multiple noise types
- DWT-based signal decomposition
- Soft thresholding for noise removal
- Signal reconstruction
- Performance evaluation using MSE and SNR
- Visualization of clean, noisy, and denoised signals

## Technologies Used
- Python
- NumPy
- Matplotlib
- PyWavelets
- SciPy

## Methodology
1. Generate or input ECG signal
2. Add noise (baseline drift, powerline noise, EMG noise)
3. Apply Discrete Wavelet Transform (DWT)
4. Perform thresholding on wavelet coefficients
5. Reconstruct the signal using inverse DWT
6. Evaluate performance using MSE and SNR

## Performance Metrics
- Mean Squared Error (MSE)
- Signal-to-Noise Ratio (SNR)

## Project Structure
ECG-DWT-Denoising/
│── ecg_dwt_denoising.ipynb
│── README.md
│── requirements.txt

## Installation
Install required libraries using:
pip install numpy matplotlib pywavelets scipy

## Usage
Run the Jupyter Notebook file:
ecg_dwt_denoising.ipynb

## Reference
https://doi.org/10.3991/ijoe.v13i09.7159

## Future Enhancements
- Use real ECG datasets (MIT-BIH)
- Compare different wavelets (db4, sym4, coif5)
- Implement advanced thresholding techniques
- Build real-time ECG denoising system

## Author
Bhanu Praneeth,Avinash
