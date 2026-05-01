# Rohan Kumar Singh

**Embedded Systems Engineer · STM32 Developer · DSP & On-Device AI**

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohankumar17362@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rohan-kumar-singh-b31465268)

---

## About

I am an Embedded Systems engineer specializing in bare-metal firmware development, real-time digital signal processing, and on-device machine learning on ARM Cortex-M microcontrollers. My work focuses on designing efficient, low-latency pipelines that run entirely on constrained hardware — no operating system, no cloud dependency.

My primary research interest lies in deploying AI inference at the edge: extracting meaningful features from raw sensor data and classifying them in real time within the tight memory and compute budgets of microcontrollers.

---

## Technical Skills

**Microcontrollers & Architecture**
STM32 (F4, F0 Series) · ARM Cortex-M4 / Cortex-M0 · Bare-Metal (Register-Level) Programming · HAL & LL Driver Abstraction · FreeRTOS

**Peripherals & Communication Protocols**
ADC · DMA · Timers · External Interrupts · UART · SPI · I2C · CMSIS-DSP Library · ST-Link · JTAG/SWD Debugging

**Signal Processing & Embedded AI**
Digital Signal Processing (DSP) · Speech Feature Extraction · MFCC · STFT · Non-Negative Matrix Factorization (NMF) · Real-Time Audio Acquisition · NanoEdge AI Studio · TinyML Inference

**Development Tools**
STM32CubeIDE · STM32CubeMX · STM32 Cube Programmer · Keil uVision · Eclipse · MATLAB · Python · KiCad · LTSpice · Altium Designer · Vivado · ModelSim · Vitis

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

**Speech-Based Parkinson's Disease Detection — STM32F401RE Nucleo**

A hardware implementation of a speech-based neurological disease classifier running entirely on an STM32F401RE Nucleo board. The system captures audio via ADC with DMA, extracts features through parallel MFCC and STFT/NMF pipelines in bare-metal C, and performs binary classification using a NanoEdge AI model deployed directly on-chip. No OS. No external compute.

`Bare-Metal C` `CMSIS-DSP` `NanoEdge AI` `ADC/DMA` `STM32F401RE`

---

**ARCH — Real-Time Voice Assistant on STM32**

A lightweight, hardware-accelerated voice assistant designed for deployment on STM32 microcontrollers. Focused on achieving low-latency speech recognition and response execution within the resource constraints of embedded hardware.

`Embedded AI` `Speech Recognition` `STM32` `Real-Time Systems`

---

## Certifications

- Embedded C Programming — Udemy
- Embedded Bare Metal Programming (STM32) — Udemy
- CPS Design using Embedded C — Coursera
- Advanced Research Internship — BIT Mesra

---

*Open to embedded systems, firmware, and DSP roles. Feel free to explore the repositories or reach out.*
