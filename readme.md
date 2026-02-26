# 🌊 PI MONIT – Group 4  
## Marine Animal Tracking System  

**Schick Benoit · Warpelin Daryl · Jeyapalan Jeyapiragash · Zweifel Robin**

---

## 📌 Project Overview

This project focuses on the design of an embedded tracking module intended to be attached to marine animals.

The primary objective is to monitor animal movements in order to:

- Better understand behavioural patterns  
- Analyse migratory routes  
- Identify critical marine areas requiring protection  

Beyond behavioural research, marine animals provide a unique and valuable platform for carrying environmental sensors. Their ability to travel long distances and dive to great depths enables data collection in regions that are difficult — or impossible — for humans to access.

Our system is designed to measure **ocean temperature as a function of depth**, contributing to climate research. Ocean temperature plays a crucial role in regulating ocean currents, which in turn significantly influence the planet’s global thermal balance.

The device must satisfy both **animal tracking** and **oceanographic measurement** requirements, while operating reliably under extreme marine conditions.

---

## 🌊 Mechanical & Environmental Constraints

The module must withstand harsh deep-sea conditions for extended periods.

### Pressure Resistance

- Fully waterproof housing  
- Designed to resist pressures equivalent to **1,000 m depth** (to be confirmed)  
- Some marine species dive beyond 1,000 m  

### Corrosion & Environmental Resistance

- Long-term exposure to seawater  
- Resistance to:
  - Salinity  
  - Thermal variations  
  - Biological fouling  

### Duration

- Minimum operational lifespan: **1 month**  
- Corresponds to a typical migration cycle  

### Structural Integrity

- Housing must maintain mechanical integrity despite:
  - High pressure  
  - Temperature changes  
  - Continuous environmental stress  

---

## ⚡ Electronic Constraints & Specifications

The embedded system must operate autonomously for at least **one month**.

### Power Optimization Strategy

- Optimised electronic architecture  
- Deep sleep operating modes  
- Careful selection of ultra-low-power components  

### Required Sensors

The module must integrate:

- 🌡️ **Temperature sensor**  
- 📏 **Pressure sensor** (for depth measurement and data validation)

These measurements form the foundation of the ocean monitoring component of the project.

---

## 📍 Localisation System

A GPS module must be integrated to:

- Track the animal’s position  
- Associate environmental measurements with precise geographic coordinates  

Position data is essential for accurate mapping and scientific analysis.

---

## 📡 Data Communication

When the animal surfaces, the module must transmit collected data.

Because the system operates in open ocean environments, communication must be achieved via:

- 🛰️ **Satellite link** (global coverage solution)

The transmitted data is then:

- Stored in a central database  
- Prepared for processing and analysis  

---

## 📊 Data Processing & Visualisation

Collected data will be:

1. Processed and validated  
2. Made accessible via a web platform  
3. Presented through interactive visualisations  

The platform must also:

- Provide access to raw scientific data  
- Enable collaboration within the research community  

The final repository could be based on the EMODnet portal  
(European Marine Observation and Data Network).

---

## 🎯 Project Goals Summary

- ✔ Long-term autonomous marine monitoring  
- ✔ Behavioural tracking of marine species  
- ✔ Ocean temperature profiling by depth  
- ✔ Satellite-based data transmission  
- ✔ Open scientific data access  
- ✔ Contribution to climate research  

---

> PI MONIT aims to combine embedded systems engineering, oceanography, and data science to support marine conservation and climate research.
