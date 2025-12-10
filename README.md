# Smart Attendance Management System

**Smart Attendance Management System** is a camera-based, face-recognition-driven attendance tracker built using **Python**, **OpenCV**, and **face_recognition**. Developed as part of my **B.Tech Mini Project** under the **SmartInternz Externship Program – Machine Learning & Deep Learning (Powered by Google Developers)**.

This system automates attendance logging through real-time facial recognition, eliminating manual intervention while maintaining high accuracy and data integrity.

---

## 1. Project Overview

This project demonstrates the integration of computer vision and deep learning to automate attendance marking.  
It identifies registered individuals from a dataset using a webcam and records their attendance automatically into a log file.

### Key Objectives
- Improve efficiency and accuracy in attendance management  
- Replace traditional paper/manual systems with intelligent automation  
- Provide a scalable solution adaptable for academic and corporate environments  

---

## 2. Features

- Real-time face detection and recognition using `dlib` and `face_recognition`  
- Automated attendance marking with timestamps  
- Flask-based lightweight web interface  
- Attendance logs stored in CSV format  
- Modular and customizable architecture  
- Platform-independent setup  
- No external database dependency  

---

## 3. Technology Stack

| Category | Technologies |
|-----------|--------------|
| **Language** | Python 3.10 |
| **Libraries** | OpenCV, Flask, NumPy, Pandas, face_recognition |
| **Build Tools** | CMake, Visual Studio C++ Build Tools |
| **Framework** | Flask |
| **Operating System** | Windows 10 / 11 |
| **Data Storage** | CSV-based logs |

---

## 4. Externship Certification

This project was completed as part of the **SmartInternz Externship Program** in **Machine Learning & Deep Learning (2023)**, powered by Google Developers.

- **Certificate ID:** Ext–2023–69195  
- **Issued Date:** November 16, 2023  
- **Program Manager:** Jayaprakash. C  

**Certification Link:** [View Certificate on Google Drive](https://drive.google.com/file/d/1ZWRW2sDFVjXbtk_q5Q7SF7bJqawvImNY/view?usp=sharing)

---

## 5. Installation and Setup Guide

Follow the steps below to install and run this project on your local machine.

### Step 1: Clone or Download the Repository
git clone https://github.com/PasupuletiThrilok/Smart-Attendance-Management-System.git
cd Smart-Attendance-Management-System
Alternatively, download the ZIP file and extract it.

### Step 2: Create and Activate a Virtual Environment
python -m venv .venv
.\.venv\Scripts\activate      # For Windows
#### or
source .venv/bin/activate     # For Linux/Mac

### Step 3: Upgrade Pip and Install Dependencies
python -m pip install --upgrade pip setuptools wheel ||
pip install -r requirements.txt 
#### If face_recognition fails during installation:
- Ensure CMake is installed system-wide and added to PATH.
- Ensure Microsoft Visual Studio C++ Build Tools (Desktop Development with C++) are installed.

### Step 4: Run the Application
python main.py
- Once the Flask server starts, open your browser and visit: http://127.0.0.1:8000 or http://192.168.0.108:8000 (local host address)

---
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/7fd07b52-8c6c-48cf-87b5-bcce03a0b80d" />

---
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/c91c1d51-9f46-49ae-b367-35aa55f1ec9c" />

---
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/a5edfff7-1794-4644-ba3b-524ba4f6533a" />

---
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/9712bf2a-1bb5-42a7-8b1c-fef1ea13df0d" />

---
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/114f14cb-0752-4c29-bb4a-dd72342bffb8" />

---
## 6. Future Enhancements
- Potential improvements for future contributors include:
- Integration with SQL databases (MySQL/SQLite) for persistent storage
- Addition of dashboard analytics for attendance visualization
- Implementation of admin authentication and access management
- Support for multiple camera feeds
- Cloud deployment on AWS, Render, or Heroku
- Development of a mobile app interface using Flutter or React Native

## 7. Author
Pasupuleti Thrilok ||
**Email:** thrilokpvc@gmail.com (Can Contact for any queries)

## 8. License
MIT License

Copyright (c) 2023 Pasupuleti Thrilok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this project and associated files, to deal
in the project without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the project, and to permit persons to whom the project is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the project.

## 9. Contribution Guidelines
Contributions, issue reports, and feature requests are welcome.

To contribute:

### Fork the repository
#### Create a new branch
git checkout -b feature-name

#### Make your changes
git commit -m "Added new feature: <description>"

#### Push your branch
git push origin feature-name
Then, open a Pull Request describing your contribution.
