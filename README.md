# 🐾 Smart Pet Care House – Automated Pet Wellness System   

An intelligent, sensor-driven automation system that ensures timely feeding, hydration, and food safety for pets. Designed to improve pet health while reducing the manual effort of daily care routines, this project integrates **custom-built sensors** and **actuators** — all controlled through **NI LabVIEW**.  

---

##  Project Overview  

The **Smart Pet Care House** introduces a modern approach to pet care by automating essential tasks such as food dispensing, water monitoring, and spoiled food detection. With rising pet ownership and increasingly busy lifestyles, maintaining consistent feeding schedules and proper hygiene is often a challenge for pet owners.  

This system provides a **reliable, safe, and fully automated solution** to those problems by combining low-cost sensors, real-time monitoring, and automated control logic.  

---

##  Objectives  

- **Automatic Food Dispensing** based on pet weight.  
- **Water Level Monitoring** and alerting when refills are needed.  
- **Spoiled Food Detection** using an ammonia gas sensor.  
- **Consistent Feeding, Hydration, and Safety** for pets.  
- **Minimize Manual Effort** for pet owners while improving pet well-being.  

---

##  Background & Context  

Traditionally, pet owners manually ensure food, water, and safety for their pets. However, irregular feeding times, empty water bowls, or spoiled food often occur due to busy lifestyles, leading to possible pet health issues.  

By leveraging **sensor technologies** and **automation platforms** such as LabVIEW and Arduino, these repetitive tasks can be automated:  
- Adjusting food portions according to pet weight  
- Monitoring and alerting for low water levels  
- Detecting ammonia gas from spoiled food  

This project demonstrates how embedded technologies can make **pet care more reliable and efficient**.  

---

##  Project Scope  

- Three main sensors:  
  - **Weight Sensor** (custom-built) – for weight-based food portioning  
  - **Ultrasonic Sensor** – for water level monitoring  
  - **Ammonia Gas Sensor** – for spoiled food detection  

- Actuation:  
  - **Servo Motor 1** – controls food dispensing  
  - **Servo Motor 2** – rotates ammonia sensor to scan food containers  
  - **LED + Buzzer Alerts** – notify owners of spoiled food or low water  

- Real-time system design in **NI LabVIEW** (sensor input handling, actuator control, decision logic).  

---

##  Methodology  

1. **System Design**  
   - Circuit diagram and layout created.  
   - Sensors selected: weight, ultrasonic, ammonia.  
   - LabVIEW used as the main controller.  

2. **Weight-Based Food Dispensing**  
   - Pet stands on the weight sensor platform.  
   - Classified into size categories (small/medium/large).  
   - Appropriate food portion dispensed via servo motor.  

3. **Water Level Monitoring**  
   - Ultrasonic sensor measures water bowl levels.  
   - Alerts triggered when below threshold.  

4. **Spoiled Food Detection**  
   - Ammonia gas sensor mounted on a servo motor.  
   - Sweeps across containers in **30° steps**, pausing for detection.  
   - If spoiled food detected → LED alert and motor stops until food is removed.  

5. **Testing & Calibration**  
   - Sensor thresholds tuned in controlled conditions.  
   - Full system tested to ensure stable operation and reliability.  

---

## Skills & Experience Gained  

- Sensor integration and calibration  
- Real-time automation using NI LabVIEW  
- Custom hardware development  
- Automation for pet health and safety  

---

##  Team Members  

- Sithmini Dhananjana  
- Dilhara Geeganage  
- Kashmira Devinda  

---

  

