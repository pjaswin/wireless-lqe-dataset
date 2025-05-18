# Wireless Link Quality Classification Dataset

## 📄 Description

This dataset contains network data collected from an indoor wireless testbed to study the generalization of machine learning models for **Link Quality Estimation (LQE)**. The dataset was used in the study: _"Quantifying Model Drift in Machine Learning for Estimating Wireless Link Quality"_.

## 🧪 Data Collection

The data was collected using a real-time indoor testbed consisting of five Wi-Fi routers deployed in adjacent office rooms. Each router operated in a controlled, single-link transmission setup where only one transmitter–receiver pair was active at a time. The transmission power was varied between 12 dBm and 20 dBm to introduce controlled changes in link characteristics.


## 📁 Contents

- Each `.csv` file contains the time-series network data for a specific link between two nodes.
- Each row represents one transmission sample with extracted features like:
  - RSSI (Received Signal Strength Indicator)
  - Noise level
  - Bitrate
  - Jitter
  - Duration
- Files are named to indicate the sender and receiver nodes (e.g., `s0_s1.csv`).

## 📜 License

You may reuse this dataset for research and educational purposes. If used, please cite the original paper.

---

