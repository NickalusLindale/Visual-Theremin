# Terpsitone  
*An open-source reconstruction of Theremin’s forgotten performance instrument.*

---

## Overview  

**Terpsitone** is a modern reimagining of Léon Theremin’s lost gesture-controlled instrument.  
This project combines **MediaPipe**, **TouchDesigner** for real-time tracking, and **Max/MSP** for dynamic sound synthesis.  

It transforms the space around a performer into a musical interface — where movement becomes music and presence becomes performance.  

Explore the full design philosophy, development notes, and technical breakdowns in the [📘 Project Wiki](https://github.com/NickalusLindale/Terpsitone/wiki).  

---

## 🛠️ Getting Started  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/NickalusLindale/Terpsitone.git

2. **Install Dependencies**
* TouchDesigner
* Max/MSP
* Compatible camera + system drivers
* MediaPipe
   * This folder MUST be extracted and placed in the same folder as the .toe projects (_See_ Wiki for complete folder organization)

3. Hardware Setup
  * Mount your infrared camera above or in front of the performance area
  * See calibration tips in the Wiki Setup Guide

4. Run the Instrument

* Launch the .toe file in TouchDesigner
* Open 2025-4-27_synthesizer_0-1.maxpat in Max/MSP

## ✨ Features

🎥 Real-time gesture and motion tracking via camera  

🔊 Generative sound synthesis with mapped motion parameters  

🎛 Signal routing with OSC between computers  

🎨 Open-source and artist-customizable

## 📁 Project Structure
```/touchdesigner/``` — Visual motion tracking + OSC output

```/maxmsp/``` — Sound generation patches

```/docs/``` — Process notes and conceptual background

```/examples/``` — Demo scenes for performances

## 🧪 Current Limitations

IR camera performance may vary across systems  

Calibration process still requires manual fine-tuning  

Audio artifacts may occur with mismatched sample rates  

See Known Issues for more.  

## 🤝 Contributing

Interested in expanding the Terpsitone? Please check the Contributing Guide and share your ideas, fixes, or extensions.  



