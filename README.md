# Nano-Learn

This is a program intended to consolidate quantitative simulation and experimental data from MFH and MPS. A machine learning algorithm is used to extrapolate predictions for numerical values, such as scaled SLP values (for MFH), and harmonic amplitudes (for MPS).

## Instructions for use

Download the relevant pkl files (or zip files containing pkl files). The relevant models are:  

**slpmodel:** predicts SLP values from simulation data  
**slpmodel-exp:** predicts SLP values from experimental data

**mpsmodel-ratio:** predicts ratio of 5th:3rd MPS harmonic amplitudes from simulation data  
**mpsmodel-ratio-frozen:** predicts ratio of 5th:3rd MPS harmonic amplitudes from simulation data with Brownian relaxation off
**mpsmodel-tau:** predicts relaxation time from MPS simulation data  
**mpsmodel-tau-frozen:** predicts relaxation time from MPS simulation data with Brownian relaxation off
**mpsmodel-tan:** predicts phase lag (omega x tau) from MPS simulation data  
**mpsmodel-tan-frozen:** predicts phase lag (omega x tau) from MPS simulation data with Brownian relaxation off

Run the relevant prediction notebook (slp_predict_from_sim, slp_predict_from_exp, mps_predict_from_sim).