# 🔧 Analog Blocks  
A structured collection of my analog circuit learnings, schematics, simulations, and analysis notes.  
This repository documents my journey in understanding and designing fundamental analog building blocks used in amplifiers, op‑amps, and mixed‑signal systems.

---

## 📘 Purpose of This Repository
This repo serves as:
- A personal **learning archive** for analog circuit design  
- A **reference library** for future projects  
- A **portfolio** showcasing practical simulations and analysis  
- A place to store **schematics, documents, and LTspice/Cadence results**  

---

## 📂 Contents
This repository will include multiple analog building blocks such as:

- Differential pairs (NMOS/PMOS)
- Current mirrors (basic, Wilson, cascode)
- Common-source, common-gate, and source-follower amplifiers
- Active loads and biasing circuits
- Gain, bandwidth, and AC analysis notes
- Transient simulations and waveform interpretations

Each block will contain:
- ✅ Schematics  
- ✅ Simulation files  
- ✅ Hand calculations  
- ✅ Notes and explanations  
- ✅ Documents (.docx, .pdf)  

---

## 📄 Detailed File Description  
### **NMOS Differential Pair with PMOS Active Load**  
**File:** `Nmos_diffpair_Pmos_activeload.docx`

This document contains a complete analysis of an **NMOS differential pair** using a **PMOS active load**, including:

#### ✅ Schematic Overview
- NMOS transistors form the differential input stage  
- PMOS transistors act as the active load  
- Output is taken from the differential-to-single-ended node  
- Classic topology used in op‑amp input stages  

#### ✅ AC Analysis
- VIN+ = 1 V AC magnitude, 1 mV amplitude  
- VIN− = 1 V AC magnitude, 180° phase shift, 1 mV amplitude  
- Differential gain defined as:  
  \[
  A_v = \frac{V_{out}}{V_{IN+} - V_{IN-}}
  \]

#### ✅ Results
- **Low-frequency gain:** ~38.45 dB  
- **−3 dB bandwidth point:** 35.45 dB  
- Gain roll‑off observed as expected for differential pair with active load  

#### ✅ Transient Analysis
- Input amplitude: 1 mV  
- Output waveform is clean and sinusoidal  
- No clipping → confirms **linear operation**  
- Transient gain (~32 dB) matches AC analysis closely  

#### ✅ What This Demonstrates
- Understanding of differential pair behavior  
- Ability to extract gain and bandwidth  
- Simulation‑based validation of linearity  
- Practical analog design workflow  

---

## 🛠 Tools Used
- MATLAB / Python (optional)  
- Hand calculations  

---

## 🧑‍💻 Author
**Naga Gowtham Mosali**  
Master’s student | Analog design learner | Circuit enthusiast  
