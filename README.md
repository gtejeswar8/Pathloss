Symbolic Regression Driven Path Loss Modeling

This repository contains a mobility-aware wireless path loss modeling framework designed to generate high-fidelity, machine-learning-ready datasets for next-generation wireless networks.

The project integrates 3GPP-compliant channel models, realistic mobility dynamics, and symbolic regression with Kalman and Markov features to accurately model path loss, SINR, and network reliability across diverse deployment scenarios.

Project Overview

Accurate path loss modeling is critical for modern wireless systems, especially in dense urban, vehicular, and mmWave environments where mobility and interference strongly affect performance.

This framework provides:

Unified modeling of mobility, channel propagation, and scheduling

Support for UMi, UMa, RMa, and Highway scenarios

Realistic simulation of LOS/NLOS, shadowing, Doppler fading, and interference

Generation of labeled datasets suitable for machine learning and benchmarking

Key Features

3GPP TR 38.901 path loss models

Mobility-aware simulation (random waypoint, vehicular, group mobility)

mmWave and sub-6 GHz support

SINR-driven handovers and OFDMA scheduling

Symbolic regression enhanced with Kalman filtering and Markov features

Comparative evaluation with classical and ML-based path loss models

What the Repository Contains

Simulation code for wireless channel and mobility modeling

Feature extraction for SINR, RSRP, Doppler shift, delay spread, and handovers

Notebooks/scripts for model comparison and performance evaluation

ML-ready datasets for reliability and path loss prediction

Applications

Wireless network planning and optimization

Mobility-aware channel modeling

Machine learning–based path loss prediction

Benchmarking classical vs data-driven propagation models

Publication

This repository supports the paper:

“Symbolic Regression Driven Path Loss Modeling with Kalman and Markov Features”
International Conference on Signal Processing, Computation, Electronics, Power and Telecommunication (IConSCEPT 2025)
