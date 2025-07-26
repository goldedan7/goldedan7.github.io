---
title: "Brake Disc Simulation"
excerpt: "This project models the heat transfer and thermal stress of a disc brake system during and after repeated braking events.  
Simulations are performed using Python and simple physics-based models to approximate real-world vehicle braking conditions."

categories:
  - Engineering Projects

toc: true
toc_sticky: true

date: 2022-07-24
last_modified_at: 2025-26-JUL
---

## 🦥 
Project Summary
**Author:** Changhyeon Lee  
**University of Bristol – Mechanical Engineering (BEng)**  
**Simulation Tools:** Python, NumPy, Matplotlib  
**Focus Areas:** Heat transfer, Newton’s cooling law, energy conversion, thermal stress

# 🔧 Disc Brake Thermal Simulation Project

This project models the heat transfer and thermal stress of a disc brake system during and after repeated braking events.  
Simulations are performed using Python and simple physics-based models to approximate real-world vehicle braking conditions.

---

## 📌 Project Summary

**Author:** Changhyeon Lee  
**University of Bristol – Mechanical Engineering (BEng)**  
**Simulation Tools:** Python, NumPy, Matplotlib  
**Focus Areas:** Heat transfer, Newton’s cooling law, energy conversion, thermal stress

---

## 🔬 Simulations Included

### 1. Repeated Braking Temperature Simulation (`brake_temp_simulation.py`)

- Models vehicle braking events occurring at fixed intervals
- Calculates disc temperature rise from braking energy
- Applies Newton's Law of Cooling between events
- Plots real-time disc temperature changes

📈 Output:  
![Repeated Braking Temp](images/repeated_braking.png)

---

### 2. Single Braking Event + Thermal Stress (`brake_stress_analysis.py`)

- Estimates disc temperature rise from kinetic energy
- Simulates cooling after braking
- Calculates induced thermal stress from temperature gradient

📉 Output:  
![Cooling Curve](images/cooling_curve.png)

---

## ⚙️ Physical Parameters

| Parameter                   | Value               |
|----------------------------|---------------------|
| Disc Material              | AISI 420 Stainless Steel |
| Specific Heat (Cp)         | 460 J/kg·K          |
| Thermal Conductivity (Kt)  | 24.9 W/m·K          |
| Disc Radius / Thickness    | 80 mm / 2 mm        |
| Convective Area            | 0.04 m²             |
| Vehicle Mass               | 1860 kg             |
| Initial Speed              | 25 m/s (~90 km/h)   |
| Brake Efficiency           | 70%                 |

---

## 🧠 Learning Outcomes

- Applied lumped capacitance model to simulate cooling
- Visualized time-dependent temperature variation in brake discs
- Estimated thermal stress using simplified mechanical models
- Practiced real-world problem solving using Python scripting

---

## 📂 File Descriptions

| File                        | Description                            |
|-----------------------------|----------------------------------------|
| `brake_temp_simulation.py` | Simulates temperature over time due to repeated braking |
| `brake_stress_analysis.py` | Simulates a single brake event, calculates thermal stress |
| `images/`                  | Saved plot results                     |
| `docs/project_report.md`   | Detailed project breakdown (optional)  |

---

## 📈 Sample Equations

**Kinetic Energy Conversion to Heat**  
Q = 0.5 × m × v² × η
ΔT = Q / (m_disc × Cp)


**Cooling: Newton’s Law**  
T(t) = T_ambient + (T0 - T_ambient) × exp(-k·t)

**Thermal Stress Approximation**  

σ = E × α × ΔT / (1 - ν)


---

## 📜 License

This project is released under the MIT License.

---

## 🔗 Contact

If you'd like to know more about this project or collaborate, please connect with me:

📧 Email: golde0715@gmail.com  
🔗 LinkedIn: [changhyeon-lee](https://www.linkedin.com/in/changhyeon-lee-329685232)




