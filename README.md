# Omkar Jadhav | Senior Embedded Systems & Edge AI Engineer

**Embedded C/C++ | ARM Cortex-M | FreeRTOS | TinyML | Hardware-in-the-Loop (HIL) | BESS & Automotive**

## 🚀 Profile Summary

Senior Embedded Systems Engineer bridging the gap between mission-critical firmware and on-device Artificial Intelligence. With 4+ years of tier-1 R&D experience (Mercedes-Benz, Fluence), I specialize in architecting real-time, deterministic software systems for resource-constrained hardware. 

My expertise spans from low-level **C/C++ RTOS development** to deploying highly optimized **TinyML / Edge AI pipelines (Quantization-Aware Training, TensorFlow Lite Micro)** natively onto microcontrollers. By combining robust firmware architecture with deep **Hardware-in-the-Loop (HIL)** validation experience, I design intelligent embedded systems that are both highly capable and rigorously tested for the Automotive and Battery Energy Storage (BESS) industries.

---

## 🛠 Technical Skills

| Category | Tools & Technologies |
| :--- | :--- |
| **Embedded & Firmware** | Embedded C/C++, FreeRTOS, ESP32, ARM Cortex-M (STM32), Microcontroller Architecture |
| **Edge AI & TinyML** | TensorFlow Lite for Microcontrollers (TFLM), Quantization-Aware Training (QAT), INT8 Optimization, DSP Noise Filtering |
| **AI Integration** | Ollama, Local LLMs (llama.cpp), Vector Databases, RAG pipelines, NLP |
| **Hardware-in-the-Loop (HIL)** | Typhoon HIL 606, dSPACE SCALEXIO, MiL/SiL/HiL Validation |
| **Test Automation & Scripting** | Python (PyTest, unittest), CAPL, ProveTech, VB.NET |
| **Modeling & Simulation** | MATLAB/Simulink, FMI/FMU, Typhoon Schematic Editor |
| **Protocols & Diagnostics** | CAN, LIN, FlexRay, MODBUS, MQTT, Ethernet, CANoe, INCA, SCADA |
| **Standards & Methodologies** | ASPICE, ISO 26262 (Functional Safety), Agile / V-Model |

---

## 📈 Professional Experience

### **Fluence (A Siemens and AES Company)**
*Senior Embedded Systems Engineer | Sep 2024 – Present* 

*   **Firmware Architecture & Grid Validation:** Architected high-fidelity, closed-loop **Hardware-in-the-Loop (HIL)** models (Typhoon HIL) to validate real-time microcontroller performance for Utility-Scale Battery Energy Storage Systems (BESS) and grid-tied inverters. Evaluated critical transient responses including FRT, ROCOF, and LVRT/HVRT under strict regulatory compliance.
*   **AI-Driven R&D:** Engineered an internal, privacy-first **RAG pipeline using local LLMs (Ollama)** to ingest dense engineering requirements and automatically generate actionable validation strategies, accelerating firmware test authoring in a secure environment.
*   **CI/CD & Automation Architecture:** Designed and deployed a robust, scalable **Python/PyTest** automation framework integrated directly into the CI/CD pipeline, minimizing human-in-the-loop dependencies and reducing full-system regression cycle times by **30%**.

### **Mercedes-Benz Research and Development India**
*Embedded Systems R&D Engineer | Aug 2022 – Sep 2024* 

*   **Safety-Critical Firmware Integration:** Led system-level integration and validation for powertrain ECUs in strict adherence to **ASPICE SWE.5/SWE.6** and **ISO 26262 ASIL-B/C** functional safety standards, ensuring deterministic execution of critical drivetrain logic.
*   **HIL Simulation & Test Automation:** Developed scalable, automated validation architectures on **dSPACE SCALEXIO** using CAPL, VB.NET, and Python. Optimized test execution latency, resulting in a **50% increase** in regression coverage and a **35% reduction** in manual diagnostic effort.
*   **Vehicle-to-Cloud (V2C) Telemetry:** Engineered end-to-end validation pipelines for connected-car features, verifying high-throughput data integrity across physical vehicle buses (**CAN, LIN, FlexRay**) and their respective cloud API endpoints.

---


## 💻 Featured Projects
### ⚡ [Concurrent-TinyML-FreeRTOS: Dual-Model Real-Time Scheduling](https://github.com/YOUR_GITHUB_USERNAME/concurrent-tinyml-freertos)

* **What it is:** A production-grade reference architecture for executing multiple independent Edge AI workloads (Anomaly Detection + SoC/SoH Estimation) concurrently on a single-core microcontroller. Replaces blocking superloop logic with **thread-safe, prioritized FreeRTOS tasks**, utilizing mutexes (`xSemaphore`) to prevent memory contention. Achieved zero missed real-time deadlines with a total static memory footprint under **16KB**.
* **Tech Stack:** `FreeRTOS`, `C/C++`, `TensorFlow Lite Micro`, `ARM Cortex-M/ESP32`, `Embedded Systems Architecture`, `Real-Time Scheduling`

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
