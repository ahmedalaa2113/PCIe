# PCIe Gen 6.0 Digital Design Graduation Project – Overview

## 📌 Project Description

This graduation project focuses on the **digital design and hardware implementation of a PCIe Gen 6.0–inspired system using Verilog HDL**. The main objective is to explore how modern high-speed communication protocols can be translated into structured digital logic, emphasizing modular design, scalability, and efficient hardware architecture. The project highlights the engineering aspects of building a PCIe-based design from a **digital design perspective**, rather than purely theoretical research.

## 🧩 Architecture Approach – The Three PCIe Layers

Our design follows the core PCIe layered architecture, where each layer is implemented as a dedicated digital module:

### 🔹 Transaction Layer

Responsible for creating and managing Transaction Layer Packets (TLPs), handling requests and completions, and organizing data flow between higher-level logic and the PCIe stack. The focus here is on packet structure, buffering, and control logic implemented in Verilog.

### 🔹 Data Link Layer

Ensures reliable communication between devices by managing packet sequencing, acknowledgments, and error handling mechanisms. This layer is designed with digital logic blocks that simulate link reliability, data integrity checks, and flow control.

### 🔹 Physical Layer (Digital Perspective)

While full analog signaling is outside the project scope, the Physical Layer is approached from a **digital design viewpoint**, including encoding concepts inspired by PCIe Gen 6.0 such as FLIT-based data handling and high-speed data formatting. The goal is to model the digital interface and data movement rather than the electrical characteristics.

## 🎯 Project Goals

* Design a **Verilog-based PCIe Gen 6.0 digital architecture** following the three-layer model.
* Build modular and reusable HDL components representing PCIe functionality.
* Apply digital design principles such as pipelining, FSM design, and timing-aware logic.
* Simulate and verify system behavior using testbenches and waveform analysis.
* Develop a scalable framework that reflects real-world hardware design workflows.

## 🧠 Technical Focus

* Digital System Design using Verilog HDL
* PCIe Gen 6.0 Architecture Concepts
* Transaction, Data Link, and Physical Layer Modeling
* High-Speed Digital Communication Principles

## 🔮 Vision

Our vision is to translate advanced PCIe Gen 6.0 concepts into a practical digital design experience. By building the layered architecture in Verilog, we aim to strengthen our expertise in hardware development, system-level thinking, and modern digital interface design aligned with industry practices.
