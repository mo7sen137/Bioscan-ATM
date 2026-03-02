# 🏥 BIOSCAN ATM
> **Self-Service Health Kiosk with Cyberpunk UI & Real-time Cloud Synchronization.**

<div align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/UI-Cyberpunk_Neon-00f3ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Security-Firebase_Auth-ffca28?style=for-the-badge&logo=firebase" />
</div>

---

## 📌 Table of Contents
* [About the Project](#-about-the-project)
* [Key Features](#-key-features)
* [Tech Stack](#-tech-stack)
* [Hardware Setup](#-hardware-setup)
* [UI Gallery](#-ui-gallery)
* [The Team](#-the-team)

---

## 📖 About the Project
**Bioscan ATM** هو مشروع تخرج مبتكر يهدف إلى تقديم فحوصات طبية ذاتية وسريعة. من خلال دمج الأنظمة المدمجة (Embedded Systems) مع تقنيات الويب الحديثة، يتيح الجهاز للمستخدمين قياس علاماتهم الحيوية (الحرارة، النبض، الضغط، ونسبة الأكسجين) ومتابعتها لحظياً عبر واجهة مستخدم مستوحاة من أسلوب الـ **Cyberpunk**.

---

## ✨ Key Features
* 🛡️ **Advanced Security:** نظام تسجيل دخول مؤمن بـ Phone OTP عبر Firebase لضمان خصوصية البيانات الطبية.
* 🧬 **Biometric Integration:** دعم حساس البصمة (R307) للتعرف السريع بين هوية المستخدم المادية وملفه الرقمي.
* ⚡ **Live Diagnostics:** تحديث فوري للبيانات من الحساسات إلى لوحة التحكم (Dashboard) عبر تقنيات الـ Real-time.
* 📊 **Data Archiving:** حفظ سجلات الفحص (History) بشكل منظم تحت رقم الموبايل الخاص بكل مريض.
* 📍 **Device Management:** نظام تتبع جغرافي للأجهزة الموزعة في المحافظات والمناطق المختلفة.

---

## 💻 Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Web Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| **Cloud Backend** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black) (Authentication & Realtime Database) |
| **Embedded** | ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white) |

---

## 🔌 Hardware Setup
الجهاز يعتمد على نظام هاردوير متقدم لضمان دقة القياسات وتفاعلية المستخدم:
### 1. وحدات المعالجة (Processing Units)

* **ESP32:** للربط السحابي ومزامنة البيانات مع Firebase.
* **Arduino Uno:** لإدارة الحساسات وتنسيق القراءات.

### 2. الحساسات الطبية والقياس (Sensors)
* **MLX90614:** لقياس درجة حرارة الجسم عن بعد.
* **Max30102:** لقياس نسبة الأكسجين (SPO2) ونبضات القلب.
* **Blood Pressure Sensor:** لقياس ضغط الدم الانقباضي والانبساطي.
* **Ultrasonic Sensor:** لحساب طول المستخدم بدقة.
* **Load Cells & HX711 Amplifier:** لقياس وزن المستخدم وتحويل الإشارات التماثلية لبيانات رقمية.
* **R307 Fingerprint Sensor:** للتعرف الحيوي على هوية المرضى.

### 3. واجهة التفاعل والتنبيه (HMI & Feedback)
* **Keypad:** لإدخال البيانات يدوياً عند الحاجة.
* **LCD Displays:** لعرض القراءات والتعليمات مباشرة للمستخدم.
* **LEDs & Buzzers:** لتوفير تنبيهات بصرية وصوتية أثناء عملية الفحص وحالات الطوارئ.
---

## 🖼️ UI Gallery
### Main Dashboard
*(Add your Dashboard screenshot link here)*
> واجهة القياسات الحيوية بتصميم النيون والـ Glassmorphism.

---

## 👥 The Team

| Avatar | Member Name | Role |
| :---: | :--- | :--- |
| 👩‍💻 | **Eng/ Lamiaa Ibrahim Muhammed** | Web Developer |
| 👩‍💻 | **Eng/ Fatema Muhammed Saad** | Web Developer |
| 👨‍💻 | **Eng/ Kariem Hisham Mansour** | Web Developer |
| 👨‍💻 | **Eng/ Mohsen Muhammed Elsaid** | IOT & Embedded system |
| 👨‍💻 | **Eng/ Mohammed Abdel Monem Rashad** | IOT & Embedded system |
| 👨‍💻 | **Eng/ Hossam Hassan Abdelaziz** | IOT & Embedded system |
| 👨‍💻 | **Eng/ Mohammed Alaa Eldin Karam** | IOT & Embedded system |

---
