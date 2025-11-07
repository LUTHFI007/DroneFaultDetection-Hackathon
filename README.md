# 🛠️ Drone Health Guard

**Drone Health Guard** is an AI-powered predictive maintenance system designed to revolutionize drone fleet management.  
Instead of waiting for failures, our system uses **machine learning on drone sensor data** to predict faults before they occur — improving safety, reliability, and cost efficiency.

---

## 🚀 Overview

Every year, **15% of commercial drones fail** during operations, costing businesses an average of **$4,200 per incident** and several hours of downtime.  
Drone Health Guard transforms this reactive maintenance model into a **proactive AI-driven approach**.

### Key Achievements:
- **74% accuracy** in detecting and classifying four distinct fault types.
- Predicts failures **30+ minutes before** they occur.
- Provides **fault type, severity assessment, and maintenance recommendations**.
- Potential savings: **$2,000+ per drone annually**.

---

## 🎯 Problem Statement

**Drone failures cost businesses millions.**

- 15% of commercial drones fail annually  
- Average repair + downtime cost: $4,200 + 8 hours  
- Safety risks in logistics, inspection, and urban operations  
- Current maintenance is **reactive**, not predictive

---

## 💡 Our Solution

**Drone Health Guard** leverages AI to:
- Detect fault types and severity in real time  
- Generate actionable maintenance alerts  
- Reduce downtime and prevent in-flight failures  
- Improve operational safety and reliability

---

## 📊 Dataset

- **Source:** Real operational drone data (with induced faults)
- **Size:** 70 flight recordings
- **Sensors:** Controller, stabilizer, and drone system readings
- **Fault Classes:** 4 distinct fault types (F0–F3) with varying severity levels

---

## 🧠 Methodology

1. **Data Preprocessing** – Clean and normalize multi-sensor readings  
2. **Feature Extraction** – Derived temporal and statistical features  
3. **Model Training** – Machine learning classifiers for fault prediction  
4. **Evaluation** – Accuracy, precision, recall, F1 score  
5. **Deployment** – Integrated with a dashboard or API (optional extension)

---

## 🧩 Technologies Used

- **Python 3.x**
- **NumPy, Pandas, Scikit-learn**
- **Matplotlib, Seaborn**
- **IBM watsonx.ai** (for model training and explainability)
- **Google Colab / Jupyter Notebook**

---

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/LUTHFI007/DroneFaultDetection-Hackathon.git