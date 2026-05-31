# Simulated Data for XMRI

This repository contains the simulated time-domain data used in the paper:

"Constructing a gravitational wave analysis pipeline for extremely large-mass-ratio inspirals"

## Description

The dataset consists of simulated **XMRI** gravitational-wave signals embedded in **TianQin** detector noise and projected onto the Time-Delay Interferometry (TDI) channels.

- **Signal (A, E)**:  
  `XMRI_A_time.npy` – TDI A‑channel XMRI signal  
  `XMRI_E_time.npy` – TDI E‑channel XMRI signal

- **Noise (A, E)**:  
  `Noise_A_time.npy` – TianQin instrumental noise in A channel  
  `Noise_E_time.npy` – TianQin instrumental noise in E channel

- **Time**:  
  `time.npy` directory contains the common time array used for all signals and noise files .  

These datasets were used to validate and test the XMRI gravitational-wave data analysis pipeline presented in the paper.
