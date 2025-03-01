# 📡 Probe-fed Microstrip Patch Antenna at 5GHz  

## 📌 Overview  
This repository contains the **design, simulation, and analysis** of a **Probe-fed Microstrip Patch Antenna** optimized for **5 GHz 5G applications**. The project focuses on **antenna design, simulation steps, and performance analysis** using parameters such as **S11, VSWR, and Gain**.  

**Microstrip patch antennas** are popular for **5G communications** due to their **compact size, low profile, and ease of integration** with electronic systems. The **probe-fed method** offers efficient power transfer and controllable input impedance, making it ideal for sub-6 GHz frequency bands.  

---

## 🎯 Objectives  
✅ **Design** a probe-fed microstrip patch antenna for 5 GHz using proper **substrate and feed techniques**.  
✅ **Simulate** the antenna to evaluate **S-parameters, VSWR, and radiation patterns**.  
✅ **Optimize antenna parameters** such as **return loss, bandwidth, and gain** for 5G applications.  
✅ **Analyze results** and compare them with theoretical expectations.  

---

## 📚 Introduction  
**Probe-fed microstrip patch antennas** are widely used in **5G networks** due to their:  
- **Compact size** and **low profile**.  
- **Efficient power transfer** with controllable input impedance.  
- **Reduced spurious radiation** compared to edge-fed designs.  

**Key considerations** for designing a 5 GHz probe-fed antenna include:  
- **Substrate selection** (low-loss materials like **Rogers RT/Duroid 5880**).  
- **Patch dimensions** based on frequency and substrate properties.  
- **Feed point location** for optimal impedance matching.  

---

## 🏗️ Antenna Design  

### 📌 **Design Parameters**  
- **Frequency (fo):** 5 GHz  
- **Substrate Permittivity (𝜀r):** 4.4  
- **Substrate Thickness (h):** 1.6 mm  
- **Patch Type:** Rectangular  
- **Feed Type:** Probe-fed (coaxial feed)  

---

## 🛠️ **Antenna Components**  
1. **Patch:** Thin metallic layer acting as the radiating element.  
2. **Substrate:** **Dielectric material** (e.g., Rogers RT/Duroid 5880).  
3. **Ground Plane:** Conductive layer beneath the substrate.  
4. **Probe Feed:** Coaxial cable connecting the patch through a via in the substrate.  

---

## 📜 **Design Equations**  

### 📌 **Patch Width (W):**  
\[
W = \frac{c}{2f_0\sqrt{\frac{\epsilon_r + 1}{2}}}
\]  

### 📌 **Effective Dielectric Constant (𝜀_eff):**  
\[
\epsilon_{eff} = \frac{\epsilon_r + 1}{2} + \frac{\epsilon_r - 1}{2} \left(1 + 12\frac{h}{W}\right)^{-\frac{1}{2}}
\]  

### 📌 **Effective Length (L_eff):**  
\[
L_{eff} = \frac{c}{2f_0\sqrt{\epsilon_{eff}}}
\]  

---

## 🔄 **Simulation Steps**  

1. **Create Rectangle (Patch):** Define width and length based on frequency and substrate properties.  
2. **Create Box (Substrate):** Specify material and thickness.  
3. **Create Ground Plane:** Define a conductive rectangle beneath the substrate.  
4. **Add Probe Feed:** Insert a coaxial feed through the substrate to connect to the patch.  
5. **Assign Boundaries:**  
   - **Radiation Boundary:** Define for accurate far-field calculations.  
6. **Perform Simulation:**  
   - **S-parameters (S11) and VSWR.**  
   - **Gain and Radiation Patterns.**  
7. **Validate Design:** Run **DRC (Design Rule Check)** and **HFSS validation**.  

📷 **Antenna Model**  
![Antenna Model](https://github.com/sandesh-ar/Design-of-Probe-fed-Microstrip-Patch-Antenna-at-5GHz/blob/main/antenna%20model.png?raw=true)  

---

## 📈 **Simulation Results**  

### 🔹 **S-parameters (S11)**  
- **Return Loss:** Better than **-10 dB**.  
- **Bandwidth:** **2-5%** of center frequency.  

### 🔹 **VSWR (Voltage Standing Wave Ratio)**  
- **Ideal Range:** Between **1 to 2** for minimal reflection.  

### 🔹 **Gain and Radiation Pattern**  
- **Gain:** **5-8 dBi** with broadside radiation pattern.  
- **Half-Power Beamwidth:** Approximately **60-70 degrees**.  

📷 **S11 and VSWR Plots**  
![S11 and VSWR](https://github.com/sandesh-ar/Design-of-Probe-fed-Microstrip-Patch-Antenna-at-5GHz/blob/main/s11.png?raw=true)  
![S11 and VSWR](https://github.com/sandesh-ar/Design-of-Probe-fed-Microstrip-Patch-Antenna-at-5GHz/blob/main/vswr.png?raw=true)  


📷 **3D Radiation Pattern**  
![Radiation Pattern](https://github.com/sandesh-ar/Design-of-Probe-fed-Microstrip-Patch-Antenna-at-5GHz/blob/main/radiation%20pattern.png?raw=true)  

---

## ✅ **Advantages of Probe-fed Patch Antenna**  
- ✔ **Efficient Power Transfer:** Reduced losses compared to edge-fed designs.  
- ✔ **Controllable Input Impedance:** Facilitates impedance matching.  
- ✔ **Compact Size:** Ideal for **5G and IoT applications**.  
- ✔ **Reduced Spurious Radiation:** Ensures cleaner signals.  

---

## 🚀 **Applications**  
1. **5G Communications:**  
   - **Small cell base stations** and **CPEs (Customer Premises Equipment)**.  
2. **Internet of Things (IoT):**  
   - Suitable for **compact and efficient wireless modules**.  
3. **Radar Systems:**  
   - Used in **short-range radar** for obstacle detection.  
4. **Wi-Fi Networks:**  
   - Employed in **dual-band Wi-Fi routers** for enhanced coverage.  

---

## 🏁 **Conclusion**  
The **probe-fed microstrip patch antenna** designed for **5 GHz** offers:  
- ✔ **High gain** and **broadside radiation** suitable for **5G networks**.  
- ✔ **Efficient power handling** with **low return loss and VSWR**.  
- ✔ **Compact and easy integration** for **IoT and communication systems**.  

------