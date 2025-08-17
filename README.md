# ⚽ RC Soccer Robot using Arduino

This project is an **RC Soccer Robot** built with Arduino as part of my **3rd Semester Digital Logic Design (DLD) Project** under the guidance of **Dr. Rehmat Ullah Khattak**.  
The robot is controlled wirelessly using **Bluetooth / Serial Monitor** and can move in multiple directions, adjust speed, and toggle headlights.

---

## 🔧 Hardware Components
- Arduino UNO  
- L298N Motor Driver  
- DC Motors (Left & Right)  
- Front LEDs (Headlights)  
- Buzzer / Horn (optional)  
- Bluetooth Module (HC-05/HC-06)  
- Power Supply (Battery)

---

## 💻 Features
✅ **Speed Control** – Adjustable motor speed (30% → 100%) using serial commands `1` → `q`.  
✅ **Movement Control** – Supports multiple movements:
- `F` → Forward  
- `B` → Backward  
- `L` → Left  
- `R` → Right  
- `G` → Forward Left  
- `I` → Forward Right  
- `H` → Backward Left  
- `J` → Backward Right  
- `S` → Stop  

✅ **Lighting System** – Headlights toggle with `U`.  
✅ **Serial Feedback** – Displays current speed and received command in Serial Monitor.  

---

## ⚙️ Working Principle
1. Arduino receives control commands via **Bluetooth / Serial Monitor**.  
2. **L298N Motor Driver** controls motor direction.  
3. **PWM signals** (`analogWrite`) adjust motor speed dynamically.  
4. LEDs act as headlights for realistic navigation.  
