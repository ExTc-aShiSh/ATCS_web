# Active Tremor Compensation Spoon (ATCS)

**An Arduino-based assistive device for Parkinson’s patients.**

> "Real-time tremor stabilization using IMU and servo control"

## 📌 Project Overview
Parkinson’s disease causes involuntary tremors, making daily activities like eating difficult and messy, leading to frustration and loss of independence.

**Our Solution:** We developed a low-cost self-stabilizing spoon that compensates for hand tremors in real-time. By utilizing an MPU6050 sensor and precise servo control, the spoon maintains a steady level position.

## ✨ Key Features
*   **Tremor Detection:** Real-time sensing of hand movements and tremors using a 6-axis Gyroscope & Accelerometer.
*   **Active Stabilization:** Uses PID feedback control to instruct servos to counteract unwanted motion instantly.
*   **Ergonomic Design:** Lightweight and comfortable handle designed specifically for ease of use.
*   **Open Source:** Built on affordable, accessible hardware making it a cost-effective solution.

## 🛠️ Technology Stack
*   **Microcontroller:** Arduino Nano
*   **Sensor:** MPU6050 IMU (Gyroscope & Accelerometer)
*   **Actuator:** MG90 Servo Motors
*   **Programming Language:** Embedded C
*   **Algorithm:** PID Control Algorithm

## ⚙️ Methodology
1.  **Data Acquisition:** Read raw data from MPU6050 IMU sensor.
2.  **Signal Filtering:** Apply Kalman/Complementary filter to reduce noise.
3.  **PID Computation:** Calculate error and determine corrective angle.
4.  **Actuation:** Drive servos to stabilize the spoon bowl.

## 👥 Team Members
*   Aaditay
*   Anuj
*   Ashish
*   Hemant

### Project Supervisors
*   Ms. Rita Devi
*   Ms. Pooja Sharma

## 🎓 Institution
**Department of ECE**
J N Government Engineering College, Sundernagar
Year: 2026

## 📬 Contact
*   **Email:** worklab008@gmail.com
*   **GitHub:** [View on GitHub](https://github.com/ExTc-aShiSh)
