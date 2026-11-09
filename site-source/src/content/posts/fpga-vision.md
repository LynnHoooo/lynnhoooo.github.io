---
title: "FPGA \u00d7 SoC: Real-Time Vision Pipeline"
published: 2025-09-01
updated: 2026-11-10
description: "A configurable ISP and Gigabit Ethernet video pipeline, with measured throughput of 720 Mbps and processing-to-transmission latency of 200 ms."
tags: ["FPGA", "SoC", "ISP", "UDP/IP"]
category: Embedded Hardware
lang: en
---

## Overview
May - September 2025 · **Hardware Lead**

Built an FPGA+SoC heterogeneous system around the Anlogic PH1A. The FPGA handled image acquisition, real-time ISP, PWM control, and networking; the SoC ran the operating system, scheduled peripherals, and performed edge AI inference.

## Configurable image processing
Implemented a Verilog ISP pipeline with black-level correction, demosaicing, automatic white balance, Gamma correction, filtering, and sharpening. Supported runtime algorithm switching and parameter adjustment.

## Networking & system integration
Implemented GMII/RGMII interfaces, the MAC layer, and a lightweight UDP/IP stack. Measured **720 Mbps** wired throughput and **200 ms** video processing-to-transmission latency, with redundant Wi-Fi video transmission.

## Multi-platform inference & control
Deployed LeNet on the FPGA, MobileNet on the SoC, and YOLOv8 on a PC. Developed a visual desktop application for monitoring, ISP configuration, parameter tuning, and remote control.
