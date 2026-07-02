# 6-Axis-Robotic-Arm
A 6-axis robotic arm prototype developed for Industry 4.0 applications, featuring 3D-printed mechanics, STM32/Arduino control systems, a Processing-based GUI, and Python backend data analysis for predictive maintenance.
# 6-Axis Robotic Arm Prototype for Industry 4.0 Applications

This repository contains the graduation thesis and comprehensive project documentation for a functional **6-Axis Robotic Arm Prototype** designed and manufactured to support industrial digitalization, predictive maintenance, and low-cost automation frameworks.

The complete academic thesis is available in this repository as: `6-Axis_Robotic_Arm_Graduation_Thesis.pdf`.

---

## 📌 Project Overview

This project presents an economical yet highly capable open-source solution aligned with Industry 4.0 paradigms. It covers an end-to-end engineering cycle including custom mechanical modeling, 3D additive manufacturing, dual-microcontroller hardware implementation, processing-based human-machine interface (HMI) design, and a Python-powered predictive data analysis backend.

### Key Capabilities:
*   **6-Axis Degree of Freedom (DoF):** Comprehensive kinematic range using precise servo actuation.
*   **Dual-Control Architecture:** Distributed processing splitting operations across hardware nodes.
*   **Record & Replay HMI:** Ability to manually manipulate coordinates through a graphical interface, record spatial trajectories, and execute them autonomously.
*   **Data-Driven Predictive Maintenance:** Live telemetry monitoring via a Python backend to analyze operational cycles and predict potential structural deviations or actuator degradation prior to critical thresholds.

---

## 📐 Mechanical Design & Manufacturing

The mechanical structure was fully modeled to accommodate optimal weight distribution and stress analysis before transition to manufacturing.
*   **CAD Engineering:** Modeled from scratch using **AutoCAD Fusion 360**.
*   **Additive Manufacturing:** Structural components and custom brackets were printed utilizing high-precision industrial-grade and consumer 3D printers, specifically the **Bambu Lab X1 Carbon** and **Creality Ender 3 V3**.

<img width="570" height="790" alt="Teknik Çizim" src="https://github.com/user-attachments/assets/7200d549-66aa-4829-a4bf-a9eb4a47f0f5" />

---

## 🔌 Embedded Systems & Control Architecture

The hardware topology utilizes a robust master-slave relationship to safely delegate automated replaying and sensory intake tracking.
*   **Microcontrollers:** Built primarily on **STM32 Nucleo** and **Arduino UNO** architectures.
*   **Actuators & Feedback:** High-torque servo motors paired with specialized sensor interfaces to capture telemetry logs during operation cycles.

  <img width="1039" height="1002" alt="Servo Şeması" src="https://github.com/user-attachments/assets/994c10cc-99ea-45cf-b6aa-118f27793bbe" />

  <img width="1450" height="856" alt="Arduino Bağlantısı" src="https://github.com/user-attachments/assets/f65fbf54-ce72-4b8e-bbad-3ff4fb83dfa1" />



---

## 💻 Human-Machine Interface (HMI) & Python Backend

A custom HMI was engineered to grant total structural control over execution points, paired alongside an intelligent cloud/local telemetry analytical system.
*   **GUI Interface:** Developed using **Processing software**, providing seamless manual manipulation, telemetry dashboards, and the core routine configuration console.
*   **Predictive Maintenance Framework:** Built using **Python**, analyzing real-time spatial positioning, current fluctuations, and movement consistency to forecast internal faults before damage occurrence.

<img width="1864" height="1051" alt="Gui" src="https://github.com/user-attachments/assets/ae285d45-eb07-446b-bd2a-fb5601ae78b7" />

---

📊 *This project demonstrates cross-functional execution across mechanical modeling, embedded C/C++ scripting, software GUI construction, and preventative systems data engineering.*
