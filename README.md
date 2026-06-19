<h1 align="center">Hi, I'm Pratyush Basnet 👋</h1>

<p align="center">
  <b>Embedded Systems</b> • <b>Machine Learning</b> • <b>Autonomous Robotics</b><br>
  <sub>I build systems that bridge hardware and intelligence — firmware that reads a sensor, then models that make sense of what it measures.</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/pratyush-basnet"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:basnet.pratyush@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/📍_Denmark-2E7D32?style=flat-square" alt="Location: Denmark">
</p>

---

### 🧭 About me

My top-graded (**12/12**) BSc thesis turned raw robot sensor streams into a real-time terrain classifier — exactly the kind of work I love: writing the firmware that reads a sensor, then training the models that make sense of what it measures.

- 🎓 **MSc in Engineering — Autonomous Systems** @ Technical University of Denmark (DTU), starting **Sept 2026**
- 🎓 **BSc in General Engineering — Cyber Systems** @ DTU · exchange semester at the **National University of Singapore**
- 🤖 I care about **robotics, embedded ML/AI, and autonomous systems** — shipping embedded and data-driven systems that work in the real world
- 🔭 Open to **student positions** in robotics, ML/AI, or autonomous systems
- 🌍 English · Nepali (native) · Danish (B2)

---

### 🚀 Featured projects

#### 🛰️ [Terrain Classification for a Field Robot from Intrinsic Sensors](https://github.com/Pratyush2012/BSC_Thesis_intrinsic_sensor_analysis) &nbsp;·&nbsp; `BSc thesis — 12/12`
An end-to-end ML pipeline that recognises agricultural terrain (grass, tilled soil, dirt track) under a DTU field robot using **intrinsic motion sensors alone** — accelerometer, gyroscope, and wheel odometry; no camera, LiDAR, or GNSS. Compared six model families (Random Forest, XGBoost, SVM, MLP, 1D CNN) over **189 engineered features** under run-disjoint Leave-One-Run-Out cross-validation (**macro-F1 0.87**), plus an online **CUSUM** detector that flags terrain transitions within 3–6 s. Code and labelled dataset released openly on Zenodo.
<br>`Python` · `PyTorch` · `scikit-learn` · `XGBoost` · `IMU / DSP`

#### 🎙️ [Speech Emotion Recognition (Speaker-Independent)](https://github.com/Pratyush2012/EmotionRecog) &nbsp;·&nbsp; `personal project`
A classical-ML pipeline that classifies seven emotions from speech on the TESS dataset. It extracts 80-D **MFCC** features (mean + std over 40 coefficients) with librosa and trains an **RBF-kernel SVM** — but the real focus is honest evaluation: a naive split scores >99% by secretly learning speaker identity, so it uses **speaker-independent GroupKFold** to hold out entire speakers and measure true generalisation.
<br>`Python` · `scikit-learn` · `librosa` · `MFCC / SVM`

#### 🔗 [StudocuOnChain — Decentralized Document Marketplace](https://github.com/Arnie016/StudocuOnChain) &nbsp;·&nbsp; `NUS EE4032 — top grade (A+)`
A full-stack Ethereum dApp that reimagines Studocu on-chain: uploaders stake ETH, five randomly-assigned voters review documents for rewards, and readers pay micro-fees to unlock approved, password-gated files. A **Solidity** smart contract on the Sepolia testnet handles staking, voting thresholds and payouts, while a **React** front end streams live updates directly from contract events — no polling.
<br>`Solidity` · `Ethereum` · `React` · `Web3` · `IPFS`

#### 🌊 Autonomous Algae–Mussel Growth Bioreactor (IoT Control System) &nbsp;·&nbsp; `DTU Design-Build · grade 10`
An **ESP32**-based closed-loop system that monitors and regulates algae density and water temperature for optimal mussel growth. A phototransistor handles optical-density measurement and temperature sensing, and feedback logic drives cooler, air and water motors — all live-monitored over **Adafruit IO** MQTT feeds.
<br>`ESP32` · `MQTT` · `Adafruit IO` · `Closed-loop control`

#### 🎮 STM32 Bare-Metal Firmware — Two Sensor-Driven Games &nbsp;·&nbsp; `NUS · A−`
Two real-time games on a **bare-metal STM32L4** board: interrupt-driven (EXTI) mode-switching via button double-press detection and a non-blocking game loop on SysTick timing, driving the full onboard sensor suite plus a custom **I²C** HT16K33 LED-matrix driver and a non-blocking PWM buzzer engine.
<br>`STM32` · `Embedded C` · `RTOS-style design`

> More on my profile: a Kalaha/Mancala game-AI agent and a logic-based belief-revision engine.

---

### 🛠️ Tech stack

**Languages**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C%20%2F%20Embedded%20C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![ARM](https://img.shields.io/badge/ARM%20Assembly-0091BD?style=flat-square&logo=arm&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

**ML & Data**
<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)

**Embedded & Robotics**
<br>
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)

**Web & Blockchain**
<br>
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)

**Tools**
<br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

<p align="center"><sub>Let's build things that work in the real world. ✉️ <a href="mailto:basnet.pratyush@gmail.com">basnet.pratyush@gmail.com</a></sub></p>
