## Audio comparison website

This project includes a simple website used to present **audio results from simulations and real circuit implementations**.

Live demo: https://hubjab21.github.io/

The website was built using **HTML and CSS** and allows listening to signals processed by different circuits.

---

### Content

The page contains short (~9 seconds) audio samples generated in LTspice simulations and compares them across different circuit designs.

Available sections:

* **Input signal**
  Original test signal used as a reference for all comparisons.

* **Single transistor amplifier**
  Basic amplification stage showing signal gain and distortion.

* **Amplifier with negative feedback**
  Modified version with feedback, resulting in lower distortion and more stable output.

* **Operational amplifier (LM741)**
  Simulation of an amplifier based on LM741.
  Audio analysis was limited due to long simulation time.

* **Fuzz effect**
  Nonlinear distortion producing a characteristic clipped guitar sound.

* **Noise gate**
  Reduces low-level noise and passes signals above a threshold.

* **Real implementation (fuzz effect)**
  One sample was tested on real hardware using guitar input.
  This allows comparison between simulation and actual circuit behavior.

Only the fuzz effect was verified on real hardware.
All other results come from LTspice simulations.

---

### Project structure

```
├── audio
├── images
├── index.html
├── README.md
└── style.css
```

---

### Purpose

The goal of this website is to provide a simple way to compare:

* different amplifier configurations
* analog audio effects
* differences between simulation and real-world behavior

It complements the LTspice simulations and hardware work included in this project.

---

### Future improvements

* adding real measurements for all circuits
* frequency-domain analysis (FFT)
* simple interactive controls
* integration with PCB designs (KiCad)

---

### Author

Hubert Jabłoński

