# 📡 E-Shape Microstrip Patch Antenna (2.4 GHz)

This repository contains the design, simulation, and physical fabrication files for an **E-Shape Microstrip Patch Antenna**.  
This project was completed as part of my EXTC engineering curriculum to demonstrate how geometric modifications can improve antenna bandwidth for wireless applications.

---

## 🚀 Overview

Standard rectangular patch antennas often suffer from **narrow bandwidth**.  
By introducing two parallel slots to create an **"E" shape**, additional resonant modes are generated. This effectively:

- Broadens the bandwidth  
- Improves impedance matching  
- Makes the antenna suitable for the **2.4 GHz ISM band (Wi-Fi/Bluetooth)**  

---

## 📊 Performance Summary

After simulation in **CST Studio Suite** and physical fabrication, the results were:

- **Operating Frequency:** 2.4 GHz  
- **Return Loss ($S_{11}$):** -21.43 dB *(Excellent matching)*  
- **VSWR:** 1.18  
- **Gain:** 6.51 dBi  
- **Substrate:** FR-4 ($\epsilon_r = 4.4$, $h = 1.6$ mm)

---

## 🛠️ Project Workflow

### 1. 📐 Math & Design
- Calculated patch dimensions using the **Transmission Line Model**

### 2. 💻 Simulation
- Designed and optimized using **CST Studio Suite**
- Tuned slot width and position for resonance at 2.4 GHz  

### 3. 🔧 Fabrication
- Transferred design onto **copper-clad FR-4 board**
- Used **PCB etching method**

### 4. 🧪 Testing
- Soldered **SMA connector**
- Verified antenna performance using measurement tools  

---

## 🧠 Key Learning

The biggest challenge was the **transition from simulation to hardware**.

I learned that:
- Fabrication tolerances (etching accuracy, connector placement)
- Variations in FR-4 dielectric constant  


---

