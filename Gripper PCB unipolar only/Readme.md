# 🦾 Gripper Control PCB

## 📘 Overview
This PCB is designed to control a **robotic gripper mechanism**, providing a compact, efficient interface for stepper and servo actuation using an **ESP32-S3** microcontroller module.  
It features dual **ULN2003A** driver ICs for stepper control, servo motor headers, LED indicators, and onboard communication through a **CAN transceiver** module.

---

## 🧠 Key Features

### ⚙️ Microcontroller Interface
- **MCU**: ESP32-S3 module (with integrated USB connection).
- Provides Wi-Fi, Bluetooth, and serial communication options.
- Direct GPIO routing for motor and sensor interfacing.

---

### 🔋 Power Management
- **Input Voltage**: Regulated **5V DC** input required.
- Power LED indicator for quick visual confirmation.
- Dedicated 5V rail for both logic and motor power (ensure adequate current supply).

---

### 🏎️ Motor Control
- **2 × ULN2003A Stepper Driver ICs**
  - Each controls one stepper motor.
  - Supports 4-phase unipolar stepper motors.
  - Onboard **LED indicators** for each stepper phase for debugging and activity monitoring.
- **2 × Stepper Motor Headers**
  - Plug-and-play connectors for stepper motors.
- **1 × Servo Motor Header**
  - PWM output from ESP32-S3 GPIO for servo control.

---

### 🧭 Communication
- **CAN Transceiver Module**
  - Enables CAN bus communication between the gripper and other robotic modules.
  - Suitable for distributed robotic systems or multi-node control architectures.

---

### 💡 LED Indications
| LED | Function |
|------|-----------|
| Power LED | Indicates board power status |
| Stepper LEDs | Show active motor coil phases during operation |

---

## 🔌 Connectors & Pinout

| Section | Connector | Description |
|----------|------------|-------------|
| MCU | ESP32-S3 Module | Main processor and control unit |
| Power | 5V DC Input | Regulated external power input |
| Stepper Drivers | 2 × ULN2003A | Drive circuits for stepper motors |
| Motor Headers | 2 × Stepper, 1 × Servo | Output headers for motors |
| Communication | CAN Transceiver | CAN bus connectivity |
| Indicators | LEDs | Stepper and power status |

---

## 🧾 Notes
- Use a **regulated 5V supply** capable of sourcing sufficient current for both steppers and the servo.  
- Ensure **common ground** between the power source, MCU, and CAN module.  
- Verify proper orientation when connecting stepper and servo headers.  
- Avoid powering large motors directly from USB — always use external 5V input.

---

## 🛠️ Applications
- Robotic gripper or end-effector control  
- Modular robotic arm sub-controller  
- Distributed motion control systems over CAN  
- IoT-enabled manipulators using ESP32-S3 connectivity  

---

## 📦 Repository Structure (Suggested)
