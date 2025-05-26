# RC-Band-Pass-Filter-simulation-using-LTspice
Band-Pass Filter simulation using LTspice. Allows specific frequency band to pass while attenuating low and high frequencies.
This project simulates an *RC Band-Pass Filter* in LTspice, designed to allow a specific range of frequencies to pass through while attenuating both low and high frequencies.

---

## 🔧 Circuit Parameters:
- *R1 = 10kΩ*
- *R2 = 20kΩ*
- *C1 = 1nF*
- *C2 = 100pF*
- *AC Source = 10V (AC 10)*
- *Simulation Command:* .ac dec 100 1 100Meg

---

## 📊 Frequency Response:
The simulation reveals a clear band-pass behavior where mid-range frequencies are passed with minimal attenuation, while both low and high frequencies are suppressed.  
Cutoff frequencies are defined by the RC values and result in a peak response at the center band.

---

## 📁 Files Included:
- BPF.asc: LTspice schematic file
- Filter Graph Screenshot: Frequency response plot
- Circuit Diagram Screenshot

---

## 📌 Tools Used:
- *LTspice XVII* (Analog Devices)

---

## 📎 Author  
[Vishal Singh](http://linkedin.com/in/vishal-singh-542338161)  
