## 🌐 Audio comparison website

The project includes a simple website presenting **audio results of simulations and real implementations**.

🔗 Live demo: https://hubjab21.github.io/

The website was created using **HTML and CSS** and allows listening to different audio signals processed by the designed circuits.

---

### 🎧 Content of the website

The page presents short (~8 seconds) audio samples generated in LTspice simulations and compares them between different circuits.

The following sections are available:

#### 🎸 Input signal
- original test signal (guitar-like waveform)
- serves as a reference for all comparisons

#### 🔊 Single transistor voltage amplifier
- basic amplification circuit
- demonstrates signal gain and distortion

#### 🔁 Amplifier with negative feedback
- improved version with feedback
- reduced distortion and more stable output

#### ⚙️ Operational amplifier (LM741)
- simulation of amplifier using LM741
- audio analysis was limited due to simulation complexity

#### 🎛️ Fuzz effect
- nonlinear distortion effect
- strong clipping producing characteristic “guitar fuzz” sound

#### 🔇 Noise gate
- suppresses low-level noise
- passes only signals above threshold

#### 🎸 Real implementation (fuzz effect)
- one sample was also tested on **real hardware (guitar input)**
- allows comparison between:
  - simulation
  - real circuit behavior

⚠️ Only one sound (fuzz effect) was compared with real hardware.  
All other results are based on LTspice simulations.

---

### 🗂️ Project structure

audio/
├── input.wav
├── single_transistor_voltage_amplifier.wav
├── single_transistor_voltage_amplifier_negative_feedback.wav
├── lm741_amplifier.wav
├── fuzz_effect.wav
├── fuzz_effect_guitar.wav
└── noise_gate.wav
imgs/
├── 1.png
├── 2.png
├── 3.png
├── 4.png
├── 5.png
├── 7.png
└── tlo.jpg
index.html
style.css
README.md

---

### 🧠 Purpose

The website serves as a **visual and audio comparison tool** for:

- different amplifier topologies
- nonlinear audio effects
- differences between simulation and real circuits

It complements the LTspice simulations and hardware implementations included in this repository.

---

### 🚀 Future improvements

- more real-world measurements for all circuits
- comparison plots (FFT / frequency response)
- interactive controls (gain, threshold, etc.)
- integration with PCB designs (KiCad)

---

👤 Author

Hubert Jabłoński



