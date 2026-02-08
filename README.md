# 🚗 Automotive Diagnostic Simulator (Level 2)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Automotive](https://img.shields.io/badge/Field-Automotive_Engineering-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Version_1_Simulation-green?style=for-the-badge)

An intelligent diagnostic tool simulation that bridges the gap between vehicle symptoms and ECU data. This project mimics the behavior of professional OBD-II scanners by analyzing trouble codes and engine symptoms.

## 🌟 Key Features
* **Vehicle Identification:** Collects and stores basic vehicle data (Brand, Model, Year, Engine).
* **OBD-II Engine:** A built-in database for common trouble codes (P-Codes) with detailed causes and solutions.
* **Symptom-Based Logic:** Evaluates mechanical symptoms to provide potential diagnosis.
* **Automated Reporting:** Generates a professional `auto_report.txt` after each session.
* **Activity Logging:** Keeps a timestamped history of all events in `auto_logs.txt`.

## 🧠 Knowledge Simulated
This version focuses on the **Diagnostic Thinking** process:
1.  **OBD-II Protocol:** Simulating how scanners interpret codes from the Powertrain (P).
2.  **Sensor Logic:** Understanding how a Lean condition (P0171) relates to O2 sensors and vacuum leaks.
3.  **Cause vs. Symptom:** Distinguishing between what the driver feels (Engine shaking) and what the ECU sees (Misfire P0300).

---

## 📂 Project Structure
```text
automotive-diagnostic-simulator/
├── automotive_diagnostic.py   # Main Application Logic
├── auto_logs.txt             # Auto-generated Activity Logs
└── auto_report.txt           # Final Diagnostic Report



