# 5G mmWave Network Anomaly Detection

This repository contains the code and data associated with the research on anomaly detection in 5G mmWave networks. The project is divided into three phases: simulation, anomaly injection, and machine learning/deep learning-based analysis.

## Repository Structure

├── phase1/
│ ├── 5g_scenario_simulation.cpp
│ ├── mmWave-tcp-window-newreno-normal.txt
│ ├── phase1_analysis.ipynb
│ └── phase1_dataset.txt
├── phase2/
│ └── dataset_with_anomalies.txt
├── phase3/
│ ├── dataset_with_anomalies.txt
│ └── phase3_ML_DL.ipynb
└── README.md

### Phase 1: Simulation

- **5g_scenario_simulation.cpp**: This file contains the NS-3 simulation code used to model the 5G mmWave network scenario. The simulation is configured to track RX packets, which are used for further analysis.

- **phase1_dataset.txt**: This is the dataset generated from the NS-3 simulation. It contains the RX packet tracker data, which serves as the basis for the subsequent analysis.

- **phase1_analysis.ipynb**: This Jupyter Notebook contains the code for analyzing the dataset generated from the NS-3 simulation in Phase 1. The analysis performed here sets the foundation for injecting anomalies in the next phase.

### Phase 2: Anomaly Injection

- **dataset_with_anomalies.txt**: This file contains the dataset after anomalies have been injected. The anomalies are introduced to simulate various network issues, which will be used to test the effectiveness of machine learning and deep learning models in detecting them.

### Phase 3: Machine Learning and Deep Learning Analysis

- **phase3_ML_DL.ipynb**: This Jupyter Notebook contains the machine learning and deep learning models used to analyze the dataset with injected anomalies. The goal is to train and evaluate models that can accurately detect and classify anomalies in 5G mmWave networks.
