# 🏔️ Himalayan Cascade Radar

A Streamlit-based prototype for monitoring **Land Surface Temperature (LST) trends** in high-mountain regions of Nepal using NASA MODIS data.

The project explores whether long-term warming trends can provide an early indicator of **permafrost degradation and potential mountain-slope instability**.

## 🌡️ Current Focus

The current prototype focuses on **one of three planned environmental signals**:

**Land Surface Temperature (LST)**

* 🛰️ Data source: NASA MODIS (MYD11A1)
* 📈 Measures: Surface temperature trends
* 🔥 Indicator: Long-term warming
* 🏔️ Potential implication: Permafrost thaw and reduced slope stability

Future versions will integrate two additional signals:

1. 🌡️ **LST** — Ground warming and permafrost change
2. 🧊 **InSAR** — Ice/slope surface velocity and acceleration
3. 💧 **Landsat** — Glacial lake expansion and GLOF risk

Together, these signals are intended to provide a more complete picture of mountain hazard conditions.

## 📊 Current Dashboard

The Streamlit application currently provides:

* Interactive selection of Nepal monitoring locations
* 🗺️ 3D geographic map
* 📈 10-year LST trend visualization
* 🌡️ LST warming rate (Sen's slope)
* 📊 Mann-Kendall statistical significance
* ⚠️ Risk classification
* Physical interpretation of thermal changes

### Current Monitoring Locations

* **Thame Valley** — 2024 GLOF site
* **Langtang / Lirung Massif**
* **Imja Tsho**

## 🛠️ Technologies

* Python
* Streamlit
* Pandas
* NumPy
* Plotly
* PyDeck
* NASA MODIS

## 🚀 Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🔭 Future Development

The planned system will expand from LST-only monitoring into a **three-signal mountain early-warning framework**:

```text
🌡️ MODIS LST
     ↓
Permafrost / thermal degradation
     +
🧊 InSAR
     ↓
Ice/slope acceleration
     +
💧 Landsat
     ↓
Glacial lake expansion
     ↓
🏔️ Multi-signal hazard assessment
```

> **One signal can miss a hazard. Combining temperature, movement, and water can provide a more complete picture of mountain risk.**

## ⚠️ Note

This is currently a **research prototype**. The dashboard uses pre-computed location data and simulated time-series visualization; it is not yet an operational disaster-warning system.
