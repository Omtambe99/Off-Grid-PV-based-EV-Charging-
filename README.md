
# ⚡ Off-Grid Solar-Powered EV Charging System using MATLAB/Simulink

This project presents the simulation and analysis of an **off-grid solar-powered electric vehicle (EV) charging system** developed in **MATLAB/Simulink**. The model integrates a standalone **photovoltaic (PV) system** with a **battery charging circuit** using **Maximum Power Point Tracking (MPPT)** and **State-of-Charge (SOC)-based control** to provide a sustainable and efficient EV charging solution in remote or grid-independent environments.

---

## 📌 Project Objectives

- To simulate a standalone PV-based EV charging system in Simulink.
- To implement MPPT using a PI controller for optimal power extraction.
- To design a DC-DC converter-based battery charging circuit using SOC monitoring.
- To evaluate the efficiency and stability of the EV charging process under varying conditions.

---

## ⚙️ Technologies & Tools

- **MATLAB/Simulink**
- Power Electronics Modeling
- MPPT Algorithms (PI Control-based)
- DC-DC Converters (Buck/Boost)
- State-of-Charge (SOC) Logic
- Data Visualization (Voltage, Current, SOC)

---

## 📁 Project Structure
📂 Off Grid pv-based-ev-charging-system
├── 📄 README.md
├── 📄 PV_EV_Grid.slx # Main Simulink model
├── 📄 Report.pdf # Literature review & theoretical basis
├── 📁 /media # Diagrams, plots, and screenshots
│ ├── block-diagram.png
│ └── waveform-results.png


---

## 🧩 Features & Model Description

### 🌞 1. Photovoltaic (PV) System
- Modeled a **4000W solar PV array**.
- Real-time input of **irradiance (G)** and **temperature (T)** to simulate environmental conditions.
- Output regulated using **MPPT algorithm** with a PI controller.

### 🔌 2. MPPT Control (Maximum Power Point Tracking)
- Uses **Perturb & Observe** logic with **PI control** to continuously adjust voltage for maximum power output.
- Optimizes energy harvested from the PV array.

### 🔋 3. EV Battery Charging Circuit
- Includes a **DC-DC converter** with an **EV controller** to manage charging based on **SOC**.
- Charging occurs in two phases:
  - **Constant Current (CC)**
  - **Constant Voltage (CV)**
- Uses PWM generation, current filtering (LC circuit), and SOC cutoff logic.

### 🔁 4. Bidirectional Converter & Grid Interface
- Surplus PV energy is sent to other DC loads or routed back to the grid using a **bidirectional converter**.
- Demonstrates **off-grid capability** and energy management flexibility.

### 📊 5. Result Visualization
- Scope blocks display:
  - Real-time voltage (0–350V)
  - Charging current (Ich)
  - SOC progression (51.64% upward)
- Shows stable charging behavior and efficient system control.

---

## 📸 Screenshots

### 🧱 Block Diagram  
![Block Diagram](media/block-diagram.png)

### 📉 Charging Behavior  
![Waveform Results](media/waveform-results.png)

---

## 🚀 How to Run the Project

1. Open MATLAB.
2. Load the Simulink model:  
   `PV_EV_Grid.slx`
3. Click **Run Simulation**.
4. Use the scopes to observe battery charging, MPPT response, and SOC changes.

> ⚠️ Ensure Simulink and Simscape libraries are installed.

---

## 🧠 Key Learnings & Outcomes

- Understood control system application in **renewable energy integration**.
- Simulated an efficient off-grid **EV charging station** using real-world variables.
- Applied **MPPT techniques, SOC logic**, and **power electronics principles** in a practical system.
- Explored system behavior under various solar conditions and charging demands.

---

## 🔮 Future Scope

- Integrate **AI-based control algorithms** (e.g., fuzzy logic, MPC) for smarter energy handling.
- Expand to **Vehicle-to-Grid (V2G)** architecture.
- Simulate **fast charging** and **wireless EV charging** scenarios.
- Enhance support for **multi-vehicle charging** and **smart grid feedback**.

---

## 📚 Reference Literature

This project is supported by a literature review provided in the `Report.pdf`, which consolidates existing research in the area of:

- Solar-PV integrated EV charging
- Battery management systems
- MPPT and DC converter efficiency
- EV infrastructure in Indian cities

---

## 👨‍💻 Authors

- **Om Tambe** – IEC2023125  
- **Abhinav Kumar** – IEC2023119  
- **Vishal Pandey** – IEC2023114  


Project under the guidance of **Dr. Ashutosh Kumar Singh**, IIITA.

---

## ⭐ GitHub Tags

`MATLAB` `Simulink` `Electric Vehicles` `Solar Energy` `MPPT` `DC-DC Converters` `Battery Management` `Off-Grid` `SOC Control`

---

> ✨ *Feel free to fork, star, or contribute to this project. Feedback and suggestions are welcome!*


