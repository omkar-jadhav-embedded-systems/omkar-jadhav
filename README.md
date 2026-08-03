# Omkar Jadhav | Senior Embedded Systems Engineer
**Embedded C/C++ | FreeRTOS | Edge AI | TinyML | ESP32 | BESS | HiL Validation**

## 🚀 Profile Summary
Senior Embedded Systems Validation Architect with 4 years of experience in real-time testing, test automation, and system integration for complex embedded controllers. Expert in architecting **Python-PyTest** frameworks and **HiL (Hardware-in-the-Loop)** platforms like **Typhoon HIL** and **dSPACE**. Specialized in integrating **AI-assisted workflows (LLMs & RAG)** to accelerate test authoring and improve regression efficiency.

---

## 🛠 Technical Skills

| Category | Tools & Technologies |
| :--- | :--- |
| **HiL Platforms** | Typhoon HIL 606, dSPACE SCALEXIO |
| **Automation** | Python (PyTest, unittest), CAPL, ProveTech, VB.NET, Embedded C, C++ |
| **Modeling** | MATLAB/Simulink (MiL/SiL/HiL), FMI/FMU, Typhoon Schematic Editor |
| **Protocols** | CAN, LIN, FlexRay, MQTT, Ethernet, MODBUS |
| **Diagnostics** | CANoe, INCA, TestRail, SCADA |
| **AI Integration** | Ollama, Open-source LLMs, RAG, TinyML, EdgeAI, TensorFlow lite |
| **Standards** | ASPICE, ISO 26262, Agile/V-Model |

---

## 📈 Professional Experience

### **Fluence (A Siemens and AES Company)**
*Senior Embedded Systems Engineer | Sep 2024 – Present* 
* Architected and deployed a scalable **Python-PyTest HiL automation framework** for inverter and BESS controllers.
* Implemented **AI-assisted requirement-to-test automation** using open-source LLMs and RAG pipelines.
* Integrated automation into **CI/CD pipelines**, reducing regression effort by 30%.
* Modeled BESS components for validation of grid-response scenarios including FRT, ROCOF, and LVRT/HVRT.

### **Mercedes-Benz Research and Development India**
*HiL Validation Engineer - Embedded Systems | Aug 2022 – Sep 2024* 
* Led **ASPICE SWE.5/SWE.6-aligned** firmware integration test plans for powertrain ECUs.
* Increased regression coverage by **50%** through scalable HiL test architecture and optimized simulation.
* Automated tests using Python, CAPL, and VB.NET, reducing manual effort by **35%**.
* Validated cloud-connected vehicle features by testing data flow between physical ECUs and cloud APIs.

---

## 💻 Featured Projects
### ⚡ [Concurrent-TinyML-FreeRTOS: Dual-Model Real-Time Scheduling](https://github.com/YOUR_GITHUB_USERNAME/concurrent-tinyml-freertos)

* **What it is:** A production-grade reference architecture for executing multiple independent Edge AI workloads (Anomaly Detection + SoC/SoH Estimation) concurrently on a single-core microcontroller. Replaces blocking superloop logic with **thread-safe, prioritized FreeRTOS tasks**, utilizing mutexes (`xSemaphore`) to prevent memory contention. Achieved zero missed real-time deadlines with a total static memory footprint under **16KB**.
* **Tech Stack:** `FreeRTOS`, `C/C++`, `TensorFlow Lite Micro`, `ARM Cortex-M/ESP32`, `Embedded Systems Architecture`, `Real-Time Scheduling`
* 
### 🔋 [TinyML BMS Anomaly Detection: Intelligent Edge AI](https://github.com/omkar-jadhav-embedded-systems/TinyML-BMS-Anomaly-Detection)
* **What it is:** An end-to-end TinyML pipeline for real-time hardware anomaly detection in Battery Energy Storage Systems (BESS) and Electric Vehicles (EVs). Deploys a **Quantization-Aware Autoencoder** on resource-constrained microcontrollers using **TensorFlow Lite INT8**, reducing the model size from **~343 KB to ~4 KB (>98% compression)** while enabling deterministic, low-latency, fully offline edge inference. Includes an industrial validation dashboard, automated model artifact generation (`.tflite`, `.h`, `.hex`), and a C++ inference engine with DSP-based signal filtering for safety-critical embedded applications.
* **Tech Stack:** `TensorFlow/Keras`, `TensorFlow Model Optimization (QAT)`, `TensorFlow Lite (INT8)`, `TinyML`, `Python`, `Streamlit`, `C/C++`, `DSP`, `Pandas`, `NumPy`

### 🔋[EdgeBMS-TinyML: Real-Time Battery State Estimation](https://github.com/omkar-jadhav-embedded-systems/EdgeBMS-TinyML)
* **What it is:** An ultra-low-footprint (~6.2 KB) TinyML pipeline running a deep neural network on-device to estimate battery cell State of Charge (SoC) and State of Health (SoH) simultaneously with 91.5% optimized TFLite accuracy. Auto-generates a bare-metal C++ header array (model.h) for direct microcontroller deployment.
* **Tech Stack:** `TensorFlow`, `tfmot (Quantization-Aware Training)`, `TFLite (INT8/Float32)`, `Python`, `C/C++`, `Pandas`
  
### 📊 [Local LLM Inference Performance & Hardware Benchmark](https://github.com/omkar-jadhav-embedded-systems/Local-LLM-Inference-Benchmark)
* **What it is:** A benchmarking suite to evaluate LLM performance (TPS, Latency, RAM/CPU usage) on local and embedded hardware across various temperature values.
* **Tech Stack:** `Python`, `llama.cpp`, `Ollama`, `System Monitoring`

### 🔒 [Privacy-First RAG using Local LLMs](https://github.com/omkar-jadhav-embedded-systems/Traditional-RAG-using-Local-LLM-Ollama)
* **What it is:** A fully offline Retrieval-Augmented Generation (RAG) pipeline for secure interactions with private PDFs, keeping all embeddings and computations on-device.
* **Tech Stack:** `Ollama`, `Vector Databases`, `Python`, `NLP`

### 🚁 [Dynamic UAV Wireless Charging using IRS (M.Tech Thesis)](https://github.com/omkar-jadhav-embedded-systems/UAV-Wireless-Charging-IRS)
* **What it is:** Academic research at IIT Guwahati investigating mathematical models and simulations for dynamically charging drones mid-flight using Intelligent Reflecting Surfaces (IRS) to mitigate NLoS outages.
* **Tech Stack:** `MATLAB/Simulink`, `Mathematical Modeling`, `RF Systems`, `Wireless Power Transfer`

### 🏎️ [ATV Data Acquisition & Telemetry System](https://github.com/omkar-jadhav-embedded-systems/ATV-Data-Acquisition-and-Telemetry)
* **What it is:** End-to-end telemetry system, custom PCBs, and sensor networks designed for live-tuning CVT, suspension, and wireless safety systems on Baja SAE off-road vehicles.
* **Tech Stack:** `Embedded C (Arduino/MSP430)`, `CAN Bus`, `Custom PCB (Proteus)`, `Hardware Sensors`

---
## 🎓 Education

* **M.Tech in Electrical and Electronics Engineering** | Indian Institute of Technology (IIT), Guwahati 
* **B.E. in Electronics and Telecommunication Engineering** | Government College of Engineering (GECA), Aurangabad 

---

## 📜 Certifications
* **HiL Test Automation** – Typhoon HIL, Inc. (2024) 
* **ISTQB Foundation Level (CTFL)** – edForce (2023) 
* **Machine Learning** – Coursera (2023) 
* **Functional Safety** – Knowledge of ISO 26262 concepts and testing practices

---

## 📬 Contact
* **Email:** omkar6589@gmail.com
* **Location:** Bengaluru, India
* **LinkedIn:** [OMKAR JADHAV](https://www.linkedin.com/in/omkar-jadhav-embedded-systems-engineer/)
