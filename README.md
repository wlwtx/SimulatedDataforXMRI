# Simulated Data for XMRI

This repository contains the simulated data used in the paper:

"Constructing a gravitational wave analysis pipeline for extremely large-mass-ratio inspirals"

## Description

The dataset consists of simulated XMRI gravitational-wave signals embedded in TianQin detector noise and projected onto the Time-Delay Interferometry (TDI) channels.

- **Signal (A, E)**:  
  `signal/xMRI_TDI_A.txt` – TDI A‑channel pure signal  
  `signal/xMRI_TDI_E.txt` – TDI E‑channel pure signal

- **Noise (A, E)**:  
  `noise/TianQin_TDI_A.txt` – TianQin instrumental noise in A channel  
  `noise/TianQin_TDI_E.txt` – TianQin instrumental noise in E channel

- **Time**:  
  `time/` directory contains the common time array used for all signals and noise files (e.g., `time.txt`).  
  *(If a specific file name is used, please replace the placeholder accordingly.)*

These datasets were used to validate and test the xMRI gravitational-wave data analysis pipeline presented in the paper.

## Citation

If you use these data, please cite:

T.-X. Wang, Y. Wang, A. Torres-Orjuela, et al., Constructing a Gravitational Wave Analysis Pipeline for Extremely Large-Mass-Ratio Inspirals, Physical Review D (2026).
