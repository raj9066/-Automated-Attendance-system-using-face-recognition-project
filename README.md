# -Automated-Attendance-system-using-face-recognition-project
Hello programers, to run this project you have to use some specific libraries such like 
1) face_recognition
2) cv2
3) numpy as np
4) csv
5)  os
6)  from datetime import datetime

# Face Recognition Attendance System

This project is a simple face recognition attendance system using the `face_recognition` library in Python. It captures video from the webcam, detects faces, and compares them to a pre-defined set of known faces. If a recognized face is detected, the system marks the attendance and logs the time in a CSV file.

## Features

- Face detection using the `face_recognition` library.
- Attendance logging with timestamps in a CSV file.
- Real-time display of the webcam feed with detected faces.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- face_recognition library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/face-recognition-attendance.git

   Install dependencies:

bash
copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
python attendance_system.py

Install dependencies:
Configuration
Add known faces: Place images of known individuals in the photos folder and update the known_faces_names list in the code.
Usage
Run the script using the command mentioned in the installation section.
Press 'q' to exit the application.
CSV File
The attendance data is logged in a CSV file with the filename format YYYY-MM-DD.csv.

Name	Time
raj	12:30:45
john	13:15:20
...	...
Contribution
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request or open an issue.

License
This project is licensed under the MIT License - see the LICENSE file for details.

sql
Copy code

Make sure to replace "your-username" with your actual GitHub username and update any additional information as needed. Also, consider adding a LICENSE file with the specific license you choose for your project.
