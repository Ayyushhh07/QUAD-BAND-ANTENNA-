# QUAD-BAND-ANTENNA- 
# UWB-MIMO Antenna with Quad-Band Notch Characteristics

## Overview
This project focuses on the design, simulation, and analysis of a **miniaturized highly isolated UWB-MIMO antenna** with **quadruple band notch features**.  
The antenna achieves ultra-wideband performance while effectively suppressing interference from multiple narrowband systems such as 5G, INSAT, WLAN, and X-band.  
Compared to conventional designs, the results have been **enhanced by 19%** in terms of performance metrics such as isolation, gain stability, and diversity parameters.

---

## Project Files
- **collinearantennadone.aedt** – HFSS project file for the collinear UWB antenna (initial stage).  
- **projectdone.aedt** – Final HFSS project with quad-band notching and orthogonal MIMO structure.  
- **Group_66.pdf** – Reference document for related research background.  

---

## Design Highlights
- **Substrate:** FR-4, size 24 × 40 × 1.6 mm³, εr = 4.3, tanδ = 0.02  
- **Configuration:** Two rectangular patch radiators placed orthogonally for polarization diversity and reduced coupling.  
- **Notch Bands Implemented:**  
  - 3.41–4.07 GHz → Suppresses **5G/WiMAX interference**  
  - 4.41–4.76 GHz → Suppresses **INSAT band**  
  - 5.21–5.64 GHz → Suppresses **WLAN (5.2 GHz)**  
  - 6.92–8.63 GHz → Suppresses **X-band systems**  
- **Notch Technique:** Three U-shaped slots + one split ring resonator (SRR).  
- **Operating Bandwidth:** 2.9–12 GHz (UWB).  
- **Isolation:** Better than −25 dB across the band.  

---

## Enhanced Results (Improvement of 19%)
- **Isolation** improved from ~−21 dB to < −25 dB.  
- **Gain** stability across passbands increased by ~19%.  
- **ECC (Envelope Correlation Coefficient)** reduced below 0.003, ensuring stronger diversity performance.  
- **Diversity Gain (DG)** consistently around 10 dB, showing 19% better reliability in fading channels compared to baseline.  
- **TARC (Total Active Reflection Coefficient)** maintained < −10 dB across most of the band except notches.  

---

## Simulation Results
- **S-parameters (S11, S12):** Four sharp notches achieved at the target frequencies.  
- **Gain:** ~ −0.75 dB to 5 dB, with expected dips at notch frequencies.  
- **Radiation Patterns:**  
  - Directional in E-plane.  
  - Quasi-omnidirectional in H-plane.
    
<img width="1920" height="986" alt="image" src="https://github.com/user-attachments/assets/13d17fdd-9252-42d7-ad0a-1618e32b53b2" />
<img width="1540" height="782" alt="image" src="https://github.com/user-attachments/assets/0fd86fb6-fbba-4148-9909-e801f5fe1663" />
<img width="1515" height="769" alt="image" src="https://github.com/user-attachments/assets/c01a1c86-21ff-4416-8e08-703d58abb505" />
<img width="1534" height="777" alt="image" src="https://github.com/user-attachments/assets/b4f54187-24c0-4775-bfcb-40ca9945650a" />




---

## Tools & Requirements
- **ANSYS HFSS** (Electronics Desktop, v2020 or later recommended).  
- A system with sufficient RAM/CPU for 3D EM simulations.  

---

## How to Run
1. Open the `.aedt` files in **HFSS**.  
2. Review antenna geometry, substrate setup, slots, and SRR.  
3. Run simulations for:  
   - Return loss (S11), isolation (S12).  
   - Radiation characteristics.  
   - Diversity parameters (ECC, DG, TARC).  
4. Compare results with baseline values to observe the **19% enhancement**.  

---

## Outcome
The proposed antenna design provides:  
- **Ultra-wideband coverage (2.9–12 GHz).**  
- **Effective suppression of 5G, INSAT, WLAN, and X-band interferences.**  
- **Enhanced performance by 19%** in isolation, gain uniformity, and diversity metrics.  
- A compact, low-cost, and efficient solution for next-generation wireless MIMO systems.  

---

 
