# Face Recognition Attendance System

This project is a smart attendance system built using **Python, OpenCV, and face-recognition library**.  
It detects faces using a webcam and automatically marks attendance in a CSV file.

## Features

- Real-time face detection using webcam
- Face recognition using encoding
- Automatic attendance marking
- CSV attendance record generation
- Fast and efficient recognition

## Technologies Used

- Python
- OpenCV
- face-recognition
- NumPy

## Project Structure
```
face-recognition-attendance-system
│
├── images_attendance
│   ├── person1.jpg
│   ├── person2.jpg
│
├── attendance_sheet.csv
├── attendance.py
├── requirements.txt
└── README.md
```

## How It Works

1. Images of known people are stored inside `images_attendance`.
2. The system encodes faces from these images.
3. The webcam captures live video.
4. Detected faces are compared with stored encodings.
5. If a match is found, attendance is recorded in `attendance_sheet.csv`.

