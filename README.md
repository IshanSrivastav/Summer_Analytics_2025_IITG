# Summer_Analytics_2025_IIT
An Event Held By Consulting &amp; Analytics Club, IIT Guwahati


# 🚗 Dynamic Pricing for Urban Parking Spaces (Real-Time with Pathway)

This project simulates real-time dynamic pricing for urban parking lots using Pathway's stream processing engine. The system ingests streaming data, computes demand-based features, and outputs pricing predictions in real time with interactive Bokeh visualizations.

---

## 📦 Tech Stack

| Tool        | Purpose                              |
|-------------|---------------------------------------|
| **Python**  | Data transformation & logic           |
| **Pathway** | Real-time data stream processing      |
| **Pandas**  | Initial data cleaning and formatting  |
| **Bokeh**   | Interactive plotting & real-time charts |
| **Panel**   | Dashboard and tab layout (multi-lot)  |
| **Google Colab** | Cloud execution environment     |

---

## 📊 Architecture Overview

```mermaid
graph TD
    A[dataset.csv] --> B[Data Cleaning (Pandas)]
    B --> C[Simulated Real-Time Stream (Pathway)]
    C --> D[Model 1 - Linear Pricing]
    C --> E[Model 2 - Demand-Based Pricing]
    D --> F[Price Output Stream]
    E --> F
    F --> G[Real-Time Bokeh Visualization (per lot)]
