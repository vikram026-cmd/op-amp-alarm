# 🔔 Op-Amp Based Alarm System (LTspice)

## 📌 Overview

This project demonstrates the design and simulation of an op-amp based alarm system using LTspice.
The system detects input signals (simulating door/window sensors) and triggers an alarm using a comparator and transistor switching stage.

---

## ⚙️ Circuit Description

* The input signal is applied to the non-inverting terminal of the op-amp.
* A reference voltage is generated using a resistor divider network.
* The op-amp operates as a **comparator**.
* When the input voltage exceeds the reference voltage, the output switches HIGH.
* The output drives a **PNP transistor**, which acts as a switching device.
* The transistor activates the **alarm (LED/load)**.

---

## 🧠 Key Concepts

* Op-amp comparator operation
* Voltage divider for reference generation
* Transistor as a switching device
* Threshold-based detection

---

## 🧪 Simulation Details

* **Software:** LTspice
* **Input:** Pulse signal
* **Supply Voltage:** 16V
* **Analysis:** Transient (.tran)

---

## 📊 Expected Output

* Input: Pulse waveform
* Op-amp output: HIGH/LOW switching
* Alarm output: ON/OFF response

---

## 📚 Reference

R. L. Boylestad and L. Nashelsky, *Electronic Devices and Circuit Theory*, 11th ed., Pearson, 2013.

---

## 🎯 Applications

* Door and window alarm systems
* Intruder detection systems
* Basic security circuits

---

## 🧑‍💻 Author

**Thangavikraman Ramachandran**  
B.E Electronics and Communication Engineering (Pre-final Year)

---

## ⭐ Notes

This project demonstrates practical analog circuit design and simulation using LTspice, focusing on comparator-based decision making and transistor switching behavior.
