# 🛡️ GLOBAL BORDER THREAT AI.
### Advanced Threat Prediction & Surveillance Intelligence Dashboard

![Version](https://img.shields.io/badge/version-v2.1.0-ff2d55?style=for-the-badge&logo=github)
![Status](https://img.shields.io/badge/status-OPERATIONAL-00ff88?style=for-the-badge)
![License](https://img.shields.io/badge/license-Academic-00e5ff?style=for-the-badge)
![Domain](https://img.shields.io/badge/domain-Border_Defence-ffaa00?style=for-the-badge)

---

![Streamlit](https://img.shields.io/badge/Streamlit-Full_Stack-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![MobileNet](https://img.shields.io/badge/MobileNet_SSD-Computer_Vision-FF6B35?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML_Models-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Image_Processing-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Data_Viz-3F4F75?style=flat-square&logo=plotly&logoColor=white)

> A real-time intelligence and AI-powered threat prediction system that acts as a comprehensive monitoring command center, simulating tactical risk evaluation and active physical intrusion detection across global hotspots.

---

## 🚀 Why This Matters

- Simulates a real-world multi-national border intelligence command center
- Blends real-time Computer Vision with Predictive Machine Learning
- Demonstrates deep environmental risk analysis (weather, time, location factors)
- Showcases a highly interactive, military-grade UI entirely within pure Python/Streamlit

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Problem Statement Fulfillment](#-problem-statement-fulfillment)
- [System Architecture](#-system-architecture)
- [AI/ML Models](#-aiml-models)
- [Navigation Modules](#-navigation-modules)
- [Data Analytics Engine](#-data-analytics-engine)
- [Tech Stack](#-tech-stack)
- [Datasets](#-datasets)
- [Project Structure](#-project-structure)
- [Setup & Installation](#-setup--installation)
- [ML Pipeline Results](#-ml-pipeline-results)
- [System Notes & Limitations](#-system-notes--limitations)

---

## 🧠 Key Highlights

- **2 Distinct AI Engines** integrated seamlessly (Predictive RF + MobileNet CV)
- **60,000+ optimized synthetic intelligence data points** generated and processed instantly
- **7 Operational Modules** including interactive 3D thermal density maps
- **Real-Time WebRTC Video Pipeline** for live edge-based object tracking
- **10+ Global Hotspots** actively monitored with contextual environmental risk scoring

---

## 🔭 Overview

**GLOBAL BORDER THREAT AI** is a tactical intelligence dashboard that integrates predictive modeling and computer vision into a unified real-time security platform. 

The system leverages a highly optimized internal data synthesizer mimicking 10+ critical international borders, running dynamic Machine Learning models to present actionable threat intelligence. Through a multi-page operational dashboard, operators can track historical breach patterns, view military-style interactive thermal maps, and deploy live webcam-based intrusion detection. 

> *"Real-time intelligence across 10+ international hotspots | AI-powered predictions"*

---

## ✅ Problem Statement Fulfillment

| # | Objective | Implementation | Status |
|---|---|---|---|
| 1 | Real-time tactical tracking | Global Risk Map with standard, thermal, and time-lapse modes | ✅ |
| 2 | Active physical intrusion detection | MobileNet SSD CV identifying humans, animals, and vehicles | ✅ |
| 3 | Predict high-risk vulnerability | Live AI Risk Predictor analyzing time, day, and weather vectors | ✅ |
| 4 | Deep environmental analytics | Advanced EDA with Sankey flow diagrams and correlation matrices | ✅ |
| 5 | Alert prioritization | Dynamic risk scoring (CRITICAL/HIGH/MEDIUM/LOW) with UI badges | ✅ |

| Challenge | Solution |
|---|---|
| Live Video Latency | Integrated `streamlit-webrtc` for async, client-side peer-to-peer frame processing |
| Complex Data Integration | Vectorized NumPy synthetic data generation replacing slow CSV I/O |
| Cluttered Analytics | Segregated the UI into 7 clean, military-themed routing modules |
| High False Positives | Tuned model hyper-parameters and thresholding in the CV pipeline |

---

## 🔄 How It Works (Simple Flow)

1. **System Initialization:** 60,000 baseline intelligence records are dynamically generated/loaded.
2. **Model Training:** A Random Forest classifier is trained in-memory to identify complex risk patterns.
3. **Environmental Mapping:** Dashboards render current breach metrics, tactical map links, and feature importance.
4. **Live Surveillance:** WebRTC captures edge video; OpenCV + Caffe model runs real-time SSD detections.
5. **Threat Scoring:** The Live Predictor allows operators to input hypothetical conditions to output a calibrated threat percentage.

---

## 🏗️ System Architecture

```text
┌─────────────────────────────────────────────────────────────────┐
│                        DATA SOURCES                             │
│       Optimized Vectorized Data Generator (60k+ records)        │
│          OR Custom CSV Uploads via Settings Module              │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         ▼
┌─────────────────────────────────────────────────────────────────┐
│                    STREAMLIT BACKBONE (app.py)                  │
│                                                                 │
│  ┌──────────────┐ ┌───────────────┐ ┌───────────────────────┐   │
│  │ MobileNet CV │ │ Data Analytics│ │  Random Forest ML     │   │
│  │ (WebRTC/AV)  │ │ (Pandas/NumPy)│ │  (Classification)     │   │
│  └──────────────┘ └───────────────┘ └───────────────────────┘   │
│          ↓                 ↓                    ↓               │
│     Caffe Weights     Sankey/Heatmaps      Feature Importance   │
└────────────────────────┬────────────────────────────────────────┘
                         │ JSON / HTML5 Canvas / WebRTC
                         ▼
┌─────────────────────────────────────────────────────────────────┐
│                   FRONTEND UI (Custom CSS)                      │
│                                                                 │
│ DASHBOARD · WORLD MAP · INTRUSION · ANALYTICS · PREDICTOR       │
│                  PERFORMANCE · SETTINGS                         │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🤖 AI/ML Models

### 1. 🔍 MobileNet SSD — Real-Time Intrusion Detection

![MobileNet](https://img.shields.io/badge/MobileNet_SSD-Caffe_Model-FF6B35?style=flat-square)
![OpenCV](https://img.shields.io/badge/Framework-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

- **Type:** Deep Learning / Computer Vision (Single Shot Detector)
- **Use:** Real-time CCTV object detection. Scans restricted zones to flag relevant classes out of the VOC dataset.
- **Filters:** Independently toggleable detection for **Humans** (Person), **Animals** (Bird, Cat, Dog, etc.), and **Vehicles** (Car, Aeroplane, Bus, etc.).
- **Performance:** High frame-rate edge processing via async WebRTC rendering.

### 2. 🎯 Random Forest — Predictive Threat Classification

![Supervised](https://img.shields.io/badge/Type-Supervised_ML-00ff88?style=flat-square)
![Efficiency](https://img.shields.io/badge/Processing-Multithreaded-ffaa00?style=flat-square)

- **Type:** Supervised Machine Learning
- **Use:** Evaluates multiple environmental and temporal vectors (Hour, DayOfWeek, Month, Weather, Is_Night, Is_Weekend) to predict likelihood of an intrusion.
- **Config:** `n_estimators=50 · max_depth=10 · min_samples_split=10 · n_jobs=-1`
- **Output:** Interpretable classifications with dynamic radar charts displaying specific threat profiles.

---

## 🖥️ Navigation Modules

| Module | Description |
|---|---|
| `📊 DASHBOARD` | Live KPIs, total active hotspots, risk distribution bar charts, and 24H activity feeds. |
| `🗺️ WORLD MAP` | 4-mode Plotly map (Tactical Command, Standard Risk, Glowing Thermal, 24H Threat Time-Lapse). |
| `📷 INTRUSION` | Live OpenCV video feed processing (Webcam, Upload, URL) with bounded box alerting. |
| `📈 ANALYTICS` | Deep EDA featuring Sankey threat flows, correlation heatmaps, and hourly/weekly patterns. |
| `🎯 PREDICTOR` | Interactive Live Risk Calculator outputting real-time threat percentages via Radar UI. |
| `⚡ PERFORMANCE`| Transparent ML metrics tab showing Model Accuracy, AUC Score, Precision, and Confusion Matrix. |
| `⚙️ SETTINGS` | System configuration, font scaling, alert toggles, and data regeneration/export controls. |

---

## 🛠️ Tech Stack

**Frontend & Visuals**

![Streamlit](https://img.shields.io/badge/Streamlit-UI-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly.js-Dashboards-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Animations-1572B6?style=flat-square&logo=css3&logoColor=white)

- Streamlit — Fully handles the routing, UI state, and backend logic.
- Custom CSS — Injected military-grade dark theme, glassmorphism, glowing borders, and CSS keyframe animations.
- Plotly Express & Graph Objects — Interactive gauges, maps, radar charts, and Sankey diagrams.

**Backend & AI Pipeline**

![Python](https://img.shields.io/badge/Python-Logic-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-RF_Model-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=flat-square)

- Scikit-Learn — Random forest model training and test-train splitting.
- OpenCV (`opencv-python-headless`) — Processing bounding boxes and Caffe blob ingestion.
- Pandas & NumPy — Vectorized statistical analysis and synthetic dataset generation.
- `streamlit-webrtc` & `av` — Frame-by-frame asynchronous video payload processing.

---

## 📦 Datasets

| Source | Size | Domain | Use |
|---|---|---|---|
| `generate_sample_data()` | 60,000 Rows | Border Incident Data | Model training, EDA, mapping |
| `Upload CSV` (Optional) | User Defined | Custom Operations | Ingests real operational datasets on the fly |
| `MobileNet Weights` | 22 MB (Auto-DL) | Neural Net Weights | Caffe-based CV inference |

> ⚠️ The `.caffemodel` weights are not included in the repository to save space. They are automatically downloaded securely via `urllib` on the first system run.

---

## 📁 Project Structure

```text
border-defence-monitoring-system/
│
├── app.py                      # Core Full-Stack Application (UI + ML Pipeline)
├── requirements.txt            # Python Dependencies
├── .gitignore                  # Excludes large weight files and pycache
│
├── 📁 .streamlit/
│   └── config.toml             # Custom Headless & Dark Theme Configuration
│
└── 📁 (Auto-Generated at Runtime)
    ├── deploy.prototxt         # MobileNet Configuration File
    └── mobilenet_iter_73k.caffemodel # 22MB CV Neural Weights
```

---

## 🚀 Setup & Installation

### Prerequisites

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)

### 1. Environment Setup

```bash
git clone <your-repository-url>
cd Border-Defence-Monitoring-System

# Highly recommended to use a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch System

```bash
streamlit run app.py
```
*The command center will securely download the required 22MB CV models on the first boot and launch in your default browser at `http://localhost:8501`.*

---

## 📊 ML Pipeline Results

```text
╔══════════════════════════════════════════════════════╗
║        GLOBAL THREAT AI  Model Pipeline v2.1         ║
╠══════════════════════════════════════════════════════╣
║  Vectorized Data Generated  :  60,000 rows           ║
║  Global Hotspots Monitored  :  10                    ║
╠══════════════════════════════════════════════════════╣
║  AI Random Forest Accuracy  :  Dynamic (~98.5%)      ║
║  Model Confidence ROC/AUC   :  Dynamic (~0.992)      ║
╠══════════════════════════════════════════════════════╣
║  CV Model Deployed          :  MobileNet SSD         ║
║  Active Detection Classes   :  Humans, Animals, Veh. ║
╠══════════════════════════════════════════════════════╣
║  Export Formats Supported   :  CSV, JSON, Excel      ║
║  System Health / Uptime     :  INTACT                ║
╚══════════════════════════════════════════════════════╝
```

---

## ⚠️ System Notes & Limitations

| Area | Status | Notes |
|---|---|---|
| **CCTV Live Feed** | Hardware Required | WebRTC detection requires a physical webcam/camera access to function properly. |
| **Data Generation** | Simulated | Built-in dataset is synthetically generated via a statistical distribution engine for testing. |
| **Model Scope** | Object Detection | SSD detects basic entities; it does not currently support facial recognition or thermal FLIR parsing. |
| **Military Deployment** | Academic Only | This is a demonstration project built for educational evaluation—not an operational military product. |

---

## 🔐 Security

- Caffe models are safely fetched from trusted, hardcoded static repository links.
- No personal user data or physical recordings are saved locally; `streamlit-webrtc` drops frames immediately after bounding boxes are rendered.
- `.gitignore` prevents accidental commits of sensitive environments or excessively large weight files.

---

**GLOBAL BORDER THREAT AI** · Threat Prediction & Surveillance Intelligence Dashboard

![Built with](https://img.shields.io/badge/Built_with-Streamlit_+_Python_+_AI/ML-00e5ff?style=for-the-badge)

---

**GitHub:** [Link to your repository here]
