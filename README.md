# 🚗 Line-Following Robot (Robot Siguelíneas)

## 📌 Project Overview  
This project involves the **design and development of an autonomous line-following robot**, built by a high school team as part of a robotics curriculum. The robot, named **"Robot Alpha Romeo"**, was developed using **Arduino**, C++ programming, and Fusion 360 for structural design. The objective was to **create a self-navigating robot that follows a black line and avoids obstacles**.

## 🎯 Objectives  
- Design and assemble a functional **line-following robot**.  
- Develop and integrate **Arduino-based programming** for motor and sensor control.  
- Troubleshoot and optimize **sensor and motor performance**.  
- Implement **obstacle detection and avoidance** features.  

## 🛠 Technologies Used  
- **Arduino Nano** for microcontroller operations.  
- **Fusion 360** for 3D modeling and base design.  
- **C++ and Arduino IDE** for programming logic.  
- **HC-SR04 Ultrasonic Sensor** for obstacle detection.  
- **TCRT5000L Infrared Sensors** for line-following capability.  
- **L298N Motor Driver** for motor control.  
- **3D-printed chassis** for structural support.  

## 📜 Project Development  
### 📅 Timeline and Key Milestones  
- **Initial Research & Planning:** Team assigned roles and defined project goals.  
- **Hardware Assembly:** Designed and printed the chassis, integrated motors and sensors.  
- **Software Development:** Coded the movement logic, including line-following and obstacle avoidance.  
- **Testing & Debugging:** Iteratively refined sensor positioning and motor responses.  
- **Final Adjustments:** Optimized sensor readings and completed the final assembly.  

### 🏗 Team Members & Roles  
- **Jorge García:** Quality control & objectives manager.  
- **Néstor Gómez:** Project coordinator & lead programmer.  
- **Iñaki Txasko:** Team spokesperson & assistant coordinator.  
- **Jorge Cabeza:** Secretary & documentation manager.  

## ⚙️ How It Works  
1. The robot moves forward while continuously scanning the surface with **TCRT5000L sensors**.  
2. When it detects a black line, it adjusts wheel speeds to stay on track.  
3. If an obstacle is detected using **HC-SR04 ultrasonic sensors**, the robot **stops, navigates around it, and then returns to the line**.  
4. The **L298N motor driver** controls the movement based on sensor input.  
5. The process runs in a continuous **loop**, making real-time adjustments.  

## 🔧 Setup Instructions  
### 📌 Prerequisites  
- **Arduino IDE** installed.  
- **Fusion 360** for 3D model modifications (optional).  
- **3D printer** (if you want to modify and print a new chassis).  

### 🔌 Hardware Setup  
1. Assemble the **3D-printed chassis**.  
2. Connect the **Arduino Nano** to the motor driver **L298N**.  
3. Attach the **TCRT5000L sensors** for line following.  
4. Connect the **HC-SR04 sensor** for obstacle detection.  
5. Power the system using a **9V battery or external power supply**.  

### 💻 Software Setup  
1. Clone this repository or download the source code.  
2. Open the Arduino IDE and upload the **main.ino** file to the Arduino Nano.  
3. Adjust sensor thresholds if needed for optimal performance.  
4. Run tests and fine-tune motor speeds based on performance.  

## 🔬 Challenges & Solutions  
### ⚠️ Challenges Faced  
- **Sensor misalignment:** Initially, the robot had difficulty distinguishing the black line from background noise.  
- **Wheel imbalance:** One wheel had inconsistent movement, causing deviations.  
- **Obstacle avoidance logic:** The robot struggled to realign after bypassing an obstacle.  

### ✅ Solutions Implemented  
- **Repositioned sensors** to be closer to the surface.  
- **Adjusted PWM values** to balance wheel rotation speeds.  
- **Refined obstacle detection logic** to improve accuracy.  

## 📷 Project Gallery  
![Robot Assembly](https://example.com/image1.jpg)  
![Testing Phase](https://example.com/image2.jpg)  

## 📌 Future Improvements  
- Implementing **machine learning** for better navigation.  
- Using a **Raspberry Pi** for advanced decision-making.  
- Improving **battery efficiency** for longer operation.  
- Adding a **Bluetooth module** for remote control capabilities.  

## 📜 License  
This project is open-source and available under the **MIT License**. Feel free to modify and improve upon our work!  

---  
💡 **"Innovation is intelligence having fun." - Albert Einstein**