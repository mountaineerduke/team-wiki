# Hardware Overview ⚙️

Welcome to the hardware documentation for our FRC robot! This section is meant for anyone who wants to understand how the robot is built, how components are connected, and where to find schematics and wiring diagrams.

---

## 🧩 What You’ll Find Here

- **Electrical Layouts** – detailed diagrams of the power distribution, motor controllers, and sensors.
- **CAN IDs & Connections** – a list of CAN devices, motor controllers, and their IDs.
- **Robot Schematics** – PDFs or images showing wiring, pneumatics, and mechanism layouts.
- **Subteam Notes** – important tips from mentors, including common pitfalls and best practices.

---

## 🔧 Electrical Overview

The robot’s electrical system is composed of:

- **Power Distribution Panel (PDP)** – central hub for power to motors, sensors, and pneumatics.
- **Motor Controllers** – Talons, Sparks, or Falcons for driving and actuating mechanisms.
- **Sensors** – encoders, limit switches, gyros, and other devices used for feedback.
- **Pneumatics** – solenoids, compressors, and cylinders for actuation.

> 💡 Tip: Always refer to the latest wiring diagram before making changes to the robot.

---

## 📦 Mechanical Overview

While software mainly interacts with electrical components, it’s important to understand:

- The layout of **drivetrain motors** and gearboxes
- Placement of **mechanisms** like arms, shooters, and intake systems
- Points where sensors are installed

This helps when mapping software to real-world hardware and troubleshooting issues.

---

## 🖼️ Schematics and Layouts

All schematics are stored in the `hardware/assets` folder (or link to your GitHub repository):

| Type | File | Description |
|------|------|-------------|
| Electrical Diagram | `electrical.pdf` | Full robot wiring diagram |
| CAN Map | `can_ids.md` | List of all CAN devices and IDs |
| Mechanism Layout | `mechanisms.png` | Physical placement of motors, sensors, and pneumatics |

---

## ⚠️ Safety Notes

- Always **power off the robot** before adjusting wiring or replacing components.
- Double-check all connections against the **latest schematics**.
- If unsure, ask a mentor before making changes to prevent damage or injury.

---

> 📝 Next Steps:
> - For detailed information about this year’s robot, see [Robot 2025 Hardware](robot-2025.md)