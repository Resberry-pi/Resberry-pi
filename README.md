<p align="center">
  <img src="https://img.shields.io/badge/Embedded%20Systems-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="Embedded Systems"/>
  <img src="https://img.shields.io/badge/Bare--Metal%20Firmware-00979D?style=for-the-badge" alt="Bare-Metal"/>
  <img src="https://img.shields.io/badge/DSP-Real--Time-blue?style=for-the-badge" alt="DSP"/>
  <img src="https://img.shields.io/badge/On--Device%20AI-TinyML-8A2BE2?style=for-the-badge" alt="TinyML"/>
  <img src="https://img.shields.io/badge/Embedded%20Cryptography-AES--128-success?style=for-the-badge" alt="Crypto"/>
</p>

<h1 align="center">Rohan Kumar Singh</h1>
<h3 align="center">Embedded Systems Engineer &nbsp;·&nbsp; STM32 Developer &nbsp;·&nbsp; DSP &amp; On-Device AI</h3>

<p align="center">
  <a href="mailto:rohankumar17362@gmail.com">
    <img src="https://img.shields.io/badge/Email-rohankumar17362@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/rohan-kumar-singh-b31465268">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
</p>

---

## About

I am an Embedded Systems engineer specializing in bare-metal firmware development, real-time digital signal processing, embedded cryptography, and on-device machine learning on ARM Cortex-M microcontrollers. My work focuses on designing efficient, low-latency pipelines that run entirely on constrained hardware — no operating system, no cloud dependency.

My primary research interest lies in deploying AI inference at the edge: extracting meaningful features from raw sensor data and classifying them in real time within the tight memory and compute budgets of microcontrollers.

---

## Technical Skills

**Microcontrollers and Architecture**

| | |
|---|---|
| Microcontrollers | STM32 (F4, F0 Series) · ARM Cortex-M4F / Cortex-M0 |
| Programming Model | Bare-Metal Register-Level · HAL and LL Driver Abstraction |
| RTOS | FreeRTOS |

**Peripherals and Communication Protocols**

| | |
|---|---|
| Data Acquisition | ADC · DMA · I2S · Timers · External Interrupts |
| Communication | UART · SPI · I2C · FSMC (8080 Parallel) |
| Libraries | CMSIS-DSP · STM32 HAL |
| Debug | ST-Link · JTAG/SWD |

**Signal Processing and Embedded AI**

| | |
|---|---|
| Feature Extraction | MFCC · GFCC · ERB Cochlear Filterbank · STFT · Spectrogram |
| Algorithms | Non-Negative Matrix Factorization (NMF) · Graph Signal Processing (GSP) · DCT-II |
| Embedded AI | NanoEdge AI Studio · TinyML Inference · KNN Classifier |
| Audio | Real-Time Audio Acquisition · I2S / ADC+DMA pipelines |

**Embedded Cryptography**

| | |
|---|---|
| Cipher | AES-128 ECB and CBC mode encryption / decryption |
| Key Generation | On-chip Hardware RNG (STM32F407 — analog noise entropy) |
| Transport | Raw binary encrypted UART streaming · Python-based host decryption |
| Library | tiny-AES-c (Public Domain) |

**Development Tools**

| | |
|---|---|
| Embedded IDE | STM32CubeIDE · STM32CubeMX · Keil uVision · Eclipse |
| Programming | STM32 Cube Programmer |
| Languages | Embedded C · Python |
| EDA / FPGA | KiCad · LTSpice · Altium Designer · Vivado · ModelSim · Vitis |
| Simulation | MATLAB |

---

## Experience

**Research Intern — BIT Mesra** `June 2025 – July 2025`

- Designed and implemented a real-time Speech-Based Parkinson's Disease Detection System on STM32F407 and STM32F030 microcontrollers
- Built an ADC + DMA-driven audio acquisition pipeline for continuous, low-latency signal capture without CPU intervention
- Developed dual feature extraction pipelines (MFCC and STFT/NMF) and integrated NanoEdge AI for on-chip classification
- Optimized firmware memory layout and execution flow to meet SRAM and flash constraints on the target hardware
- Worked with the research team on dataset validation, model accuracy evaluation, and iterative hardware testing

---

## Projects

**Bulbar-Onset ALS / Dysarthria Detection — STM32F407VET6**

Real-time motor speech disorder detection running entirely on bare-metal ARM Cortex-M4. Dual-path feature extraction (GFCC via biologically accurate ERB cochlear filterbank + STFT/NNMF) feeds a Graph Signal Processing layer that quantifies spectral, temporal, and cepstral disruptions characteristic of dysarthric speech. NanoEdge AI classifier integration in progress.

`Bare-Metal C` `GFCC` `ERB Filterbank` `GSP` `STFT/NNMF` `NanoEdge AI` `I2S` `INMP441` `STM32F407`

---

**AES-128 Secure Image Transmission — STM32F407VETx**

End-to-end encrypted image transmission over UART using AES-128-CBC. The on-chip hardware RNG generates a fresh 128-bit key and IV on every boot — no hardcoded keys in Flash. A 320x240 monochrome image is encrypted in-place and streamed as a raw binary packet (KEY + IV + CIPHERTEXT) to a Python receiver that decrypts and reconstructs the PNG. Includes an ECB baseline stage for algorithm comparison.

`Bare-Metal C` `AES-128 CBC/ECB` `Hardware RNG` `UART Streaming` `Python` `tiny-AES-c` `STM32F407`

---

**Speech-Based Parkinson's Disease Detection — STM32F401RE Nucleo**

A hardware implementation of a speech-based neurological disease classifier running entirely on an STM32F401RE Nucleo board. Audio is captured via ADC with DMA, features extracted through parallel MFCC and STFT/NMF pipelines in bare-metal C, and binary classification performed using a NanoEdge AI model deployed directly on-chip. No OS. No external compute.

`Bare-Metal C` `CMSIS-DSP` `NanoEdge AI` `ADC/DMA` `STM32F401RE`

---

**ARCH — Real-Time Voice Assistant on STM32**

A lightweight, hardware-accelerated voice assistant designed for deployment on STM32 microcontrollers. Focused on achieving low-latency speech recognition and response execution within the resource constraints of embedded hardware.

`Embedded AI` `Speech Recognition` `STM32` `Real-Time Systems`

---

## Certifications

| Certification | Platform |
|---|---|
| Embedded C Programming | Udemy |
| Embedded Bare Metal Programming (STM32) | Udemy |
| CPS Design using Embedded C | Coursera |
| Advanced Research Internship | BIT Mesra |

---

<p align="center">
  <em>Open to embedded systems, firmware, DSP, and on-device AI roles. Feel free to explore the repositories or reach out.</em>
</p>
