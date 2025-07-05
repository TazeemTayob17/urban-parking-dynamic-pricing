# 🚗 Dynamic Pricing Engine for Urban Parking Lots

**Summer Analytics 2025 Capstone Project**  
Hosted by the **Consulting & Analytics Club × Pathway**

---

## 📌 Project Overview

Urban parking spaces are a limited and high-demand resource. Static pricing often leads to overcrowding or underutilization. This project builds a **real-time dynamic pricing engine** using machine learning and economic intuition to maximize efficiency across 14 urban parking lots.

We implemented and visualized two intelligent pricing models using only Python, Pandas, Numpy, Pathway, and Bokeh — streamed and plotted in real-time using Google Colab.

---

## 🚀 Tech Stack

| Component        | Technology         |
|------------------|--------------------|
| Language         | Python 3           |
| Data Manipulation | Pandas, Numpy     |
| Real-Time Engine | [Pathway](https://pathway.com) |
| Visualization    | Bokeh, Panel       |
| Notebook Environment | Google Colab   |
| Version Control  | GitHub             |

---

## 🧠 Architecture Diagram

```plaintext
                 +--------------------+
                 |  parking_stream.csv |
                 +--------------------+
                            ↓
                    (Pathway Replay)
                            ↓
          +------------------------------+
          |   Data Preprocessing &       |
          |   Feature Engineering        |
          +------------------------------+
                            ↓
              +------------------------+
              |      Model 1:          |
              |   Baseline Pricing     |
              +------------------------+
                            ↓
              +------------------------+
              |      Model 2:          |
              |   Demand-Based Pricing |
              +------------------------+
                            ↓
         +-------------------------------+
         |    Real-Time Bokeh Plots      |
         |   (Pricing per Parking Lot)   |
         +-------------------------------+

