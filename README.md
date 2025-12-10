Smart Attendance Management System

Smart Attendance Management System is a camera-based, face-recognition-driven attendance tracker built using Python, OpenCV, and face_recognition.
Developed as part of my B.Tech Mini Project under the SmartInternz Externship Program – Machine Learning & Deep Learning (Powered by Google Developers).

This system automates attendance logging through real-time facial recognition, eliminating manual intervention while maintaining high accuracy and data integrity.

1. Project Overview

This project demonstrates the integration of computer vision and deep learning to automate attendance marking. It identifies registered individuals from a dataset using a webcam and records their attendance automatically into a log file.

Key objectives:

Enhance efficiency and accuracy in attendance management.

Replace traditional paper-based/manual systems with intelligent automation.

Provide a scalable framework for academic and corporate environments.

2. Features

Real-time face detection and recognition using dlib and face_recognition

Automated attendance marking with timestamps

Flask-based lightweight web interface for interaction

Attendance log generation in CSV format

Modular design for easy adaptation to new environments

No external database dependency

Works across multiple operating systems with minimal setup

3. Technology Stack
Category	Technologies
Language	Python 3.10
Libraries	OpenCV, Flask, NumPy, Pandas, face_recognition
Build Tools	CMake, Visual Studio C++ Build Tools
Framework	Flask
Operating System	Windows 10 / 11
Data Storage	CSV-based logs

4. Externship Certification

This project was completed as part of the SmartInternz Externship Program in Machine Learning & Deep Learning (2023), powered by Google Developers.

Certificate ID: Ext–2023–69195
Issued Date: November 16, 2023
Program Manager: Jayaprakash. C

(Certificate file: https://drive.google.com/file/d/1ZWRW2sDFVjXbtk_q5Q7SF7bJqawvImNY/view?usp=sharing)

5. Installation and Setup Guide

Follow the steps below to install and run this project on your local system.

Step 1: Clone or Download the Repository
git clone https://github.com/PasupuletiThrilok/Smart-Attendance-Management-System.git
cd Smart-Attendance-Management-System


Alternatively, you can download the ZIP file and extract it.

Step 2: Create and Activate a Virtual Environment
python -m venv .venv
.\.venv\Scripts\activate      # For Windows
# OR
source .venv/bin/activate     # For Linux/Mac

Step 3: Upgrade Pip and Install Dependencies
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt


If face_recognition fails during installation:

Ensure CMake is installed system-wide and added to PATH.

Ensure Microsoft Visual Studio C++ Build Tools (Desktop Development with C++) are installed.

Step 4: Run the Application
python main.py


Once the server starts, open your browser and navigate to:

http://127.0.0.1:8000

<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/129af2da-ce6c-4b2e-adfe-27366e8267d8" />

<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/6e3d63bf-7600-473e-912a-18d274ea594e" />

<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/888c0058-82bc-4cdf-b4ab-be4d31d5f4ab" />

<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/92208d0b-21de-4f1e-b8e5-195abf09279b" />

Step 5: Project Structure

<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/c5a09927-f25a-44c6-b7b9-c8db472f2204" />


6. Future Enhancements

Potential improvements for future contributors include:

Integration with SQL databases (MySQL/SQLite) for persistent storage

Addition of dashboard analytics for attendance visualization

Admin authentication and access management

Support for multiple camera feeds

Cloud deployment using AWS / Render / Heroku

Development of a mobile client using Flutter or React Native

7. License
MIT License

Copyright (c) 2025 Pasupuleti Thrilok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

8. Author

Pasupuleti Thrilok
Machine Learning & Deep Learning Enthusiast
Extern – SmartInternz x Google Developers (2023)
Email: thrilokpvc@gmail.com
GitHub: https://github.com/PasupuletiThrilok

9. Contribution Guidelines

Contributions, issues, and suggestions are welcome.
To contribute:

# Fork the repository
# Create a new branch for your feature or fix
git checkout -b feature-name

# Make your changes
git commit -m "Add new feature: <description>"

# Push the branch
git push origin feature-name


Then, open a Pull Request describing your modifications.
