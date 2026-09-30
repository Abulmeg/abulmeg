<div align="center">

# Adam Megdadi

### Computer Engineering @ Jordan University of Science and Technology

Software · Mobile · Embedded Systems · IoT · Machine Learning

I like building systems where software connects with hardware and real-world problems.

[LinkedIn](https://www.linkedin.com/in/abulmeg/) · [Email](mailto:abulmegdev@gmail.com)

</div>

---

## About Me

I'm a fourth-year Computer Engineering student at JUST.

Most of what I learn comes from building projects. I've worked on web and mobile applications, APIs, databases, real-time systems, Arduino and ESP32 projects, robotics, IoT, and machine learning.

I enjoy understanding how the different parts of a system work together, not just using each technology separately.

---

## Tech I Work With

<table>
<tr>
<td width="50%" valign="top">

### Languages

<p>
<img src="https://img.shields.io/badge/C++-20232a?style=flat-square&logo=cplusplus&logoColor=00599C" />
<img src="https://img.shields.io/badge/C-20232a?style=flat-square&logo=c&logoColor=A8B9CC" />
<img src="https://img.shields.io/badge/Python-20232a?style=flat-square&logo=python&logoColor=3776AB" />
<img src="https://img.shields.io/badge/JavaScript-20232a?style=flat-square&logo=javascript&logoColor=F7DF1E" />
<img src="https://img.shields.io/badge/TypeScript-20232a?style=flat-square&logo=typescript&logoColor=3178C6" />
</p>

### Mobile

<p>
<img src="https://img.shields.io/badge/React%20Native-20232a?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Expo-20232a?style=flat-square&logo=expo&logoColor=FFFFFF" />
</p>

### Data & Machine Learning

<p>
<img src="https://img.shields.io/badge/PostgreSQL-20232a?style=flat-square&logo=postgresql&logoColor=4169E1" />
<img src="https://img.shields.io/badge/Supabase-20232a?style=flat-square&logo=supabase&logoColor=3FCF8E" />
<img src="https://img.shields.io/badge/pandas-20232a?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-20232a?style=flat-square&logo=scikitlearn&logoColor=F7931E" />
<img src="https://img.shields.io/badge/Machine%20Learning-20232a?style=flat-square" />
</p>

</td>

<td width="50%" valign="top">

### Web & Backend

<p>
<img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-20232a?style=flat-square&logo=nextdotjs&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/Node.js-20232a?style=flat-square&logo=nodedotjs&logoColor=5FA04E" />
<img src="https://img.shields.io/badge/Express-20232a?style=flat-square&logo=express&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/REST%20API-20232a?style=flat-square" />
<img src="https://img.shields.io/badge/WebSocket-20232a?style=flat-square" />
</p>

### Embedded, IoT & Robotics

<p>
<img src="https://img.shields.io/badge/Arduino-20232a?style=flat-square&logo=arduino&logoColor=00979D" />
<img src="https://img.shields.io/badge/ESP32-20232a?style=flat-square&logo=espressif&logoColor=E7352C" />
<img src="https://img.shields.io/badge/MQTT-20232a?style=flat-square&logo=eclipsemosquitto&logoColor=white" />
<img src="https://img.shields.io/badge/Embedded%20Systems-20232a?style=flat-square" />
<img src="https://img.shields.io/badge/Robotics-20232a?style=flat-square" />
</p>

### Tools & Platforms

<p>
<img src="https://img.shields.io/badge/Docker-20232a?style=flat-square&logo=docker&logoColor=2496ED" />
<img src="https://img.shields.io/badge/Git-20232a?style=flat-square&logo=git&logoColor=F05032" />
<img src="https://img.shields.io/badge/Linux-20232a?style=flat-square&logo=linux&logoColor=FCC624" />
<img src="https://img.shields.io/badge/Vercel-20232a?style=flat-square&logo=vercel&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/VS%20Code-20232a?style=flat-square&logo=visualstudiocode&logoColor=007ACC" />
</p>

</td>
</tr>
</table>

---

# Selected Projects

## Smart Seed Storage IoT Platform

A full-stack IoT prototype for monitoring environmental conditions and remotely controlling equipment inside a seed storage facility.

The goal was to build the complete flow from sensor data to a live dashboard and back to equipment control.

### What it does

- Receives temperature, humidity, CO₂, light, and air-quality readings through MQTT
- Stores historical telemetry in PostgreSQL
- Updates the dashboard live using WebSocket
- Displays historical temperature and humidity trends
- Controls ventilation, cooling, and dehumidification
- Waits for controller acknowledgement before changing equipment state
- Detects environmental threshold violations
- Detects sensors that stop reporting
- Uses JWT authentication and role-based access
- Requires authenticated MQTT clients
- Runs PostgreSQL and Mosquitto through Docker

### Stack

<p>
<img src="https://img.shields.io/badge/MQTT-20232a?style=flat-square&logo=eclipsemosquitto&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-20232a?style=flat-square&logo=nodedotjs&logoColor=5FA04E" />
<img src="https://img.shields.io/badge/Express-20232a?style=flat-square&logo=express&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/PostgreSQL-20232a?style=flat-square&logo=postgresql&logoColor=4169E1" />
<img src="https://img.shields.io/badge/WebSocket-20232a?style=flat-square" />
<img src="https://img.shields.io/badge/Docker-20232a?style=flat-square&logo=docker&logoColor=2496ED" />
<img src="https://img.shields.io/badge/JWT-20232a?style=flat-square&logo=jsonwebtokens&logoColor=FFFFFF" />
</p>

[View Repository](https://github.com/Abulmeg/smart-seed-storage-iot)

---

## Rattibha

Rattibha started as a university schedule builder for students at JUST and later expanded into a web and mobile student platform.

The main idea is to make university systems easier to use from one place instead of jumping between different services.

### Website

- Search courses and sections
- Build university schedules
- Save schedules
- Work with official course and section data
- Arabic and English support
- Student authentication

### Mobile App

- Personal university schedule
- Academic information
- Registered courses
- Exams and tasks
- eLearning integration
- Notifications for academic updates
- University-service integrations
- Arabic and English interface

### Stack

<p>
<img src="https://img.shields.io/badge/Next.js-20232a?style=flat-square&logo=nextdotjs&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/TypeScript-20232a?style=flat-square&logo=typescript&logoColor=3178C6" />
<img src="https://img.shields.io/badge/React%20Native-20232a?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Expo-20232a?style=flat-square&logo=expo&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/Supabase-20232a?style=flat-square&logo=supabase&logoColor=3FCF8E" />
<img src="https://img.shields.io/badge/PostgreSQL-20232a?style=flat-square&logo=postgresql&logoColor=4169E1" />
<img src="https://img.shields.io/badge/REST%20APIs-20232a?style=flat-square" />
</p>

The main source repositories are private.

A public project overview will contain screenshots, architecture, features, and technical decisions without exposing the private source.

---

## Health Machine Learning Study

A machine learning project using three different health datasets and three different types of ML problems.

### Heart-Failure Classification

Built and compared classification models to identify patients at higher risk.

The work included class imbalance, model comparison, threshold tuning, cross-validation, and evaluation using recall, F1, and ROC-AUC.

### Body-Fat Regression

Used body measurements to estimate body-fat percentage.

Several regression approaches were compared and evaluated using MAE, RMSE, and R².

### Obesity Clustering

Used K-Means clustering to explore patterns in obesity-related data without using the existing labels as the target.

I also tested cluster stability and compared different values of K.

### What I worked on

- Data cleaning
- Exploratory data analysis
- Feature engineering
- Feature selection
- Classification
- Regression
- Clustering
- Cross-validation
- Hyperparameter tuning
- Ensemble models
- Model evaluation
- Result interpretation and limitations

### Stack

<p>
<img src="https://img.shields.io/badge/Python-20232a?style=flat-square&logo=python&logoColor=3776AB" />
<img src="https://img.shields.io/badge/pandas-20232a?style=flat-square&logo=pandas&logoColor=FFFFFF" />
<img src="https://img.shields.io/badge/scikit--learn-20232a?style=flat-square&logo=scikitlearn&logoColor=F7931E" />
<img src="https://img.shields.io/badge/Classification-20232a?style=flat-square" />
<img src="https://img.shields.io/badge/Regression-20232a?style=flat-square" />
<img src="https://img.shields.io/badge/K--Means-20232a?style=flat-square" />
</p>

Public repository coming soon.

---

## Embedded & Robotics

I've worked with Arduino and ESP32 through university courses and personal projects.

I've built projects using sensors, microcontrollers, and embedded logic, and I've also built and programmed robots for robotics competitions.

I don't really care about treating hardware and software as two completely separate things. The part I enjoy is making the entire system work together:

<div align="center">

`Sensors / Hardware → Communication → Backend → Application`

</div>

---

## Competitive Programming

### IEEEXtreme 18.0

**2nd in Jordan · Top 1% worldwide**

Competitive programming helped me improve my problem solving, algorithms, debugging, and ability to work under time pressure.

---

## Contact

**LinkedIn**  
[linkedin.com/in/abulmeg](https://www.linkedin.com/in/abulmeg/)

**Email**  
[abulmegdev@gmail.com](mailto:abulmegdev@gmail.com)
