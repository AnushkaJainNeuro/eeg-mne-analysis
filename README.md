# EEG Signal Analysis with MNE-Python

My first neurotechnology project: loading, filtering, and analyzing real EEG data.

![EEG Power Spectral Density](psd_plot.png)

## What I did
- Loaded a real EEG/MEG sample dataset using MNE-Python
- Selected the EEG channels from the recording
- Applied a 1-40 Hz bandpass filter to remove slow drift and high-frequency noise, keeping the frequency range where meaningful brain activity occurs
- Computed and plotted the power spectral density (PSD) to see how much of each frequency is present in the signal

## What I found
- A peak around 8–12 Hz, consistent with the brain's alpha rhythm
- A clear drop-off at 40 Hz, showing the effect of the bandpass filter

## The tools I used
Python, MNE-Python, Matplotlib, NumPy