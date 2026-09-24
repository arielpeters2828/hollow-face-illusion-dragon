# Hollow-Face Illusion Dragon: Optimized Mechatronic Vibrations Display

A physical and digital engineering project that combines a 3D-modeled optical illusion with an optimized mechatronic rotating unbalanced mass system. This platform evaluates structural system dynamics and validates analytical model variations against real-world sensor data.

## Project Overview & Optimization Framework
Inspired by the haptic vibration mechanisms utilized in modern mobile devices, this project focuses on the design, optimization, fabrication, and testing of a rotating unbalanced mass system configured as a custom turntable powered by a **29DCM4 DC motor**. 

The system was engineered to satisfy strict, multi-objective design constraints:
* **Target Vibration Amplitude:** Maintain a theoretical steady-state displacement response between **2.0 mm and 2.5 mm**.
* **Mathematical Optimization:** Implemented **MATLAB’s `fmincon` optimization framework** to compute optimal operational parameters. The algorithm simultaneously minimized the motor's driving frequency and mass eccentricity, successfully reducing overall power consumption and minimizing structural footprint requirements.

To integrate these technical criteria with an optical illusion theme, a classic "hollow-face" dragon assembly was reverse-engineered to serve as the custom, functional structural enclosure base.

---

## Engineering & Prototyping Process

### Phase 1: Physical to Digital Reverse-Engineering
* **Physical Assembly:** Constructed a paper-based "Thinky" Dragon illusion to establish geometric spatial baselines.
* **Metrology:** Used manual tools (protractors and rulers) to map the multi-faceted complex geometries of the illusion.
* **Parametric CAD Modeling:** Logged 40+ hours in **SolidWorks** building a 1:1 scale replica. 
  * *Note: The modeling process required iterative visual validation phases, as the digital perspective rendering continuously triggered the optical illusion during design.*

### Phase 2: Electromechanical Adaptation & Fabrication
To transition the static model into a dynamic vibrations testbed matching the computed optimization parameters, the following modifications were made:
* **Enclosure Engineering:** Excavated the internal structural base of the dragon to create space for the motor mount and reduce material waste.
* **Integrated Motor Mount:** Designed a press-fit internal mounting enclosure inside the housing to securely anchor the **29DCM4 motor**.
* **Mass Eccentricity Implementation:** Designed and 3D printed a minimalist eccentric propeller adapter featuring an offset mass hole on one end, press-fitted directly to the motor output shaft.

---

## How It Works & System Architecture

When power is supplied to the internal 29DCM4 motor, the eccentric propeller rotates rapidly to create a controlled rotating unbalanced mass condition. Because the propeller is thin, it generates relatively low vibrations.

### Data Acquisition & Instrumentation Setup
To capture system dynamics, map experimental frequencies, and evaluate discrepancies against the analytical model, the platform uses two sensor integrations:
* **Rotational Velocity:** A digital tachometer monitors and records the real-time driving frequency of the motor.
* **Structural Response:** An accelerometer mounted to the rigid housing measures the resulting vibrational acceleration vectors to calculate final displacement amplitudes.


---

## Media & Visual Proof


3D Printed Version:

<img width="426" height="240" alt="Hollow-Face Illusion Dragon_ Optimized Mechatronic Vibrations Display" src="https://github.com/user-attachments/assets/8ec42e3e-89e2-4ec0-8cb5-d0d823280c69" />


SolidWorks CAD Version (1:1 scale replica)

https://github.com/user-attachments/assets/ee5824c1-a7a7-4775-8662-f3156c13f085








