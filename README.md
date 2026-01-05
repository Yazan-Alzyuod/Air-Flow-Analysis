# Air-Flow-Analysis
# Room Airflow & Temperature Distribution – ANSYS CFD Project

## 📌 Project Overview
This project presents a Computational Fluid Dynamics (CFD) simulation of airflow and temperature distribution inside an enclosed room using **ANSYS Fluent (Student Version)**.  
The study focuses on analyzing HVAC cold air supply behavior, recirculation zones, and thermal distribution within the room.

The simulation includes velocity streamlines and temperature volume rendering to evaluate ventilation effectiveness and thermal comfort.

---

## 🎯 Objectives
- Simulate airflow induced by a cold air HVAC inlet
- Analyze velocity distribution and recirculation patterns
- Study temperature distribution within the room
- Visualize results using streamlines and volume rendering
- Produce an engineering-level CFD project suitable for portfolio use

---

## 🧱 Geometry Description
- Enclosed room domain (rectangular volume)
- Internal HVAC/device unit
- One cold air inlet and one pressure outlet
- Solid walls representing room boundaries
- Approximate room length: ~10 m (based on scale bar)

---

## 🧩 Mesh Information
Mesh data extracted from ANSYS Mesh Report:

- **Domain:** zone1  
- **Nodes:** 90,701  
- **Elements:** 506,091  

The mesh is a volumetric unstructured mesh suitable for room-scale airflow and thermal simulations.

---

## 🌬️ Physics & Boundary Conditions

### Domain Physics
- **Domain Type:** FLUID  
- **Material:** Air  
- **Energy Equation:** Enabled  

### Boundary Conditions
| Boundary Name | Type |
|--------------|------|
| cold_air_inlet | Velocity Inlet |
| return | Pressure Outlet |
| device | Wall |
| wall-1 | Wall |

---

## ⚙️ Solver Settings (ANSYS Fluent)
- Solver: Pressure-Based
- Flow Regime: Steady-State
- Turbulence Model: RANS (k-ε recommended)
- Pressure–Velocity Coupling: SIMPLE
- Discretization: Second Order Upwind
- Energy Equation: Enabled
- Initialization: Hybrid Initialization
- Convergence Criteria:
  - Residuals ≤ 1e-4
  - Energy ≤ 1e-6

---

## 📊 Results & Post-Processing

### Velocity Field
- Velocity streamlines show strong jet flow from the cold air inlet
- Large recirculation zones formed inside the room
- Maximum velocity observed ≈ **0.84 m/s**

### Temperature Distribution
- Temperature range: **289 K – 316 K**
- Cooler region near inlet
- Warmer region near device and downstream plume
- Volume rendering illustrates thermal mixing and hot spots

---

## 🖼️ Visual Outputs
The repository includes:
- Velocity streamline visualization
- Mesh and physics report screenshots
- Temperature volume rendering

All images are located in the `/images` directory.

---
**Yazan Alzyuod**
* **Mechanical Engineer**
* 📧 [yqlasem@gmail.com](mailto:yqlasem@gmail.com)
* 🔗 [LinkedIn Profile](https://www.linkedin.com/in/yazan-alzyuod)
* 💻 [GitHub Profile](https://github.com/Yazan-Alzyuod)
* 📞 00962775327776
