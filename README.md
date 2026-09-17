# smart-nursey-home-project
# 👶 Smart Nursery Guardian

### An AI-Assisted Embedded Monitoring System for Infant Care

Smart Nursery Guardian is an integrated AI and embedded system designed
to monitor an infant's condition and surrounding environment.

The system combines baby-cry classification, real-time sensor monitoring,
automated actuator control, a Python GUI, serial communication, Telegram
safety alerts, and STM32-based embedded control.

---

## 🚀 Main Features

- Baby cry classification: Hungry, Tired, and Discomfort
- MFCC-based audio feature extraction
- Machine Learning classification
- STM32 sensor monitoring
- PIR motion detection
- Temperature monitoring and automatic fan control
- Ambient-light-based lighting control
- Gas/smoke detection
- Servo-based crib rocking
- Python Tkinter GUI
- Serial communication between Python and STM32
- Telegram safety notifications
- Custom PCB design using Altium Designer

---

## 🧠 Machine Learning

Baby cry audio is processed and converted into MFCC features before
being passed to the trained Machine Learning model.

### Pipeline

Audio Input  
↓  
Audio Preprocessing  
↓  
MFCC Feature Extraction  
↓  
Machine Learning Model  
↓  
Hungry / Tired / Discomfort

---

## ⚙️ System Architecture

The system is divided into two main sides:

### Python / Laptop

- Audio processing
- Machine Learning inference
- GUI
- Telegram notifications
- Serial communication

### STM32

- Motion sensor
- Temperature sensor
- Light sensor
- Gas sensor
- Servo motor
- Cooling fan
- LEDs
- Buzzer

The STM32 and Python application communicate through serial communication.

---

## 🛠️ Technologies

### Software & Machine Learning

- Python
- Scikit-learn
- Librosa
- MFCC
- Joblib
- Tkinter

### Embedded Systems

- STM32
- UART
- ADC
- PWM
- Sensors & Actuators

### Hardware Design

- Altium Designer
- Schematic Design
- PCB Layout
