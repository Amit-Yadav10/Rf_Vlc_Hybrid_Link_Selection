# Rf_Vlc_Hybrid_Link_Selection
Utility-Driven Intelligent Link Selection for Link aggregated VLC-RF Platooning under Weather Impairments


# 🚗📡💡 RF-VLC Hybrid Link Selection using Machine Learning

An intelligent vehicular communication system that performs **dynamic link selection** between **Radio Frequency (RF)** and **Visible Light Communication (VLC)** channels using **Machine Learning** to maximize reliability, throughput, and QoS in changing environments.

🔗 **Repository:** [Rf_Vlc_Hybrid_Link_Selection](https://www.catalyzex.com/paper/optimal-design-of-energy-harvesting-hybrid?utm_source=chatgpt.com)

---

## 📌 Overview

Future Intelligent Transportation Systems (ITS) require ultra-reliable and low-latency communication. Traditional RF communication suffers from:

- Spectrum congestion  
- Interference  
- Weather attenuation  
- Limited bandwidth  

Visible Light Communication (VLC) provides:

- High-speed data transfer  
- Large unlicensed bandwidth  
- Low interference  
- Better security  

This project combines both technologies into a **Hybrid RF-VLC Communication Model**, where Machine Learning decides the **best available link in real time**.

---

## 🎯 Objectives

✅ Simulate realistic RF, VLC, and Hybrid vehicular communication environment  
✅ Generate large-scale synthetic dataset  
✅ Train ML model for optimal link selection  
✅ Improve throughput, outage probability, BER, and latency  
✅ Compare RF vs VLC vs Hybrid performance  

---

## ⚙️ Technologies Used

- **MATLAB**
- Machine Learning
- Random Forest / XGBoost / ANN
- Wireless Communication Modeling
- Vehicular Network Simulation
- Data Visualization

---

## 📊 Features Considered

The model uses dynamic network/environment parameters such as:

- Vehicle Speed
- Distance
- Fog Density
- Rain Intensity
- Ambient Noise
- RF SNR
- VLC SNR
- BER_RF
- BER_VLC
- Capacity_RF
- Capacity_VLC
- Utility Scores

---

## 🧠 ML-Based Link Selection

The trained model predicts:

| Output Class | Meaning |
|------------|---------|
| RF | Use Radio Frequency Link |
| VLC | Use Visible Light Link |
| Hybrid | Use Both Links |

---

## 📈 Performance Metrics

The project evaluates:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Capacity vs Weather
- BER vs Distance
- Utility Comparison
- Outage Probability

---

## 📂 Project Structure

```bash
Rf_Vlc_Hybrid_Link_Selection/
│── dataset/
│── models/
│── figures/
│── code/
│   ├── main.m
│   ├── train_model.m
│   ├── simulation.m
│── README.md
