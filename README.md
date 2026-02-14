# IoT-Based Supply Chain of Frozen Food Monitoring

---

## About

This is my final year project submitted as part of my Bachelor's degree in Information Technology (Hons) in Internet Of Things at Universiti Kuala Lumpur(2021 – 2025). The project explores how IoT technology can be applied to real-world supply chain challenges — specifically in monitoring frozen food during transportation and storage.

The system prototype integrates temperature sensing, real-time GPS tracking, RFID-based access control, and a live web/mobile dashboard, all connected through an ESP32 microcontroller and cloud infrastructure.

## Quick Preview

| What it monitors | How |
|---|---|
| Temperature | AHT20 sensor with real-time readings and threshold alerts |
| Lock status | Servo motor lock/unlock triggered by RFID verification |
| Access status | Logs who accessed the container — authorized ID or denied |
| Location | NEO-6M GPS with live map view |
| Speed | Real-time km/h of the transport unit |
| Product traceability | Unique QR code per frozen product |
| Transactions | Digital invoice form with supplier, receiver & QR scan |

All data is visualized on a **Node-RED dashboard** (web & mobile) and stored on **Google Cloud via Google Sheets**.

---

## Full Report

The complete project report — including literature review, system design, circuit diagrams, methodology, results, and data analysis — is available in this repository:

👉 [`IOTBASED_SUPPLY_CHAIN_OF_FROZEN_FOOD_MONITORING_MUHAMMAD_HAZIQ_BIN_ROZMAN.pdf`](./IOTBASED_SUPPLY_CHAIN_OF_FROZEN_FOOD_MONITORING_MUHAMMAD_HAZIQ_BIN_ROZMAN.pdf)
