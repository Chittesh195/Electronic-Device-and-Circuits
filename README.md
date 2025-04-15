# 🔋 Voltage Regulator Using Zener Diode

### 💡 End-Semester EDC Lab Project – Design and Simulation of a Voltage Regulator

---

## 📘 Project Description

This project demonstrates the **design and implementation of a voltage regulator** using a **3.6V Zener diode** to provide a **constant 4.1V output** from a **rectified pulsating DC input (6–8V)**. The circuit is designed to maintain voltage stability even as the **load current varies from 0 to 70 mA**.

---

## 🎯 Objective

- Design a voltage regulator that outputs a steady 4.1V from a 6V–8V input.
- Ensure proper operation across a varying load current of 0–70 mA.
- Explore the roles of capacitors, resistors, and Zener diodes in voltage regulation.

---

## 🔧 Components Used

| Component        | Specification   |
|------------------|-----------------|
| Power Supply     | 6–8 V DC Input  |
| Zener Diode      | 1N4729A (3.6V)  |
| Rectifier Diode  | 1N4007          |
| Capacitor        | 470 µF          |
| Resistors        | 56Ω, 75Ω        |
| Load             | Variable        |

---

## 🛠️ Circuit Design

- **Rectification**: AC input is converted to pulsating DC using a half-wave rectifier.
- **Filtering**: A capacitor smoothens the ripple in the pulsating DC.
- **Regulation**: A Zener diode maintains a constant output voltage.
- **Load**: Resistor emulates variable load from 0–70 mA.

---

## 📈 Results

| Input Voltage | Output Voltage | Load Current |
|---------------|----------------|--------------|
| 6 V           | 4.080 V        | 53.80 mA     |
| 7 V           | 4.096 V        | 54.02 mA     |
| 8 V           | 4.102 V        | 54.88 mA     |

- Peak voltage observed: **4.12 V**
- Maximum current measured: **55.05 mA**

---

## ✅ Conclusion

- The designed circuit successfully provides a stable **4.1V output** despite fluctuations in input voltage.
- The combination of **Zener diode**, **filter capacitor**, and **resistors** offers an effective low-cost regulation technique.
- This project serves as a strong foundation for further exploration of power electronics and voltage regulation circuits.

