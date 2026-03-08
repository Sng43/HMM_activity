**Group 18 HMM, by: Oyinwenebi Fiderikumo and Senga**


This repository presents a Hidden Markov Model (HMM)–based human activity recognition system developed using smartphone sensor data which we collected ourselves . The project collects accelerometer recordings for four activities—still, standing, walking, and jumping—using the Physics Toolbox app, and we put our phones at waist level to try and replicate a wearable health monitoring scenario. Sensor data from two phones was harmonized to a uniform sampling rate and segmented into time windows which we extracted statistical and frequency-based features from. A Hidden Markov Model was implemented from scratch using NumPy, with Baum–Welch used for parameter training and Viterbi decoding used to infer the most probable sequence of activities. The repository includes the processed dataset, feature extraction pipeline, HMM implementation, evaluation on unseen data, and visualizations such as transition matrices and predicted activity sequences, demonstrating how probabilistic models can infer hidden behavioral states from noisy sensor measurements.

Report and Team Contributions are above.
