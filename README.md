# 🚨 Motion Detection Alarm System

A Python-based Motion Detection Alarm System that uses a webcam to detect movement in real time and triggers an alarm when motion is detected.

## 📌 Project Overview

This project is a simple security surveillance system developed using Python and OpenCV. The system continuously captures video frames from a webcam, compares consecutive frames, detects motion, and alerts the user through a system alarm.

The project demonstrates basic Computer Vision concepts such as frame differencing, image thresholding, contour detection, and real-time video processing.

---

## ✨ Features

- Real-time motion detection
- Webcam-based monitoring
- Bounding box around moving objects
- Motion alert notification
- System alarm sound on detection
- Lightweight and easy to use

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- WinSound (Windows)

---

## 📂 Project Structure

```text
Motion_Detection_Alarm
│
├── motion_alarm.py
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <repository-link>
```

### 2. Navigate to the Project Folder

```bash
cd Motion_Detection_Alarm
```

### 3. Install Dependencies

```bash
pip install opencv-python numpy
```

---

## ▶️ Run the Project

```bash
python motion_alarm.py
```

---

## 🔄 Working Principle

1. Capture live video frames using webcam.
2. Compare consecutive frames.
3. Calculate frame differences.
4. Convert frames to grayscale.
5. Apply thresholding to identify moving regions.
6. Detect contours around moving objects.
7. Trigger alarm when motion is detected.
8. Display motion detection alert on screen.

---

## 📸 Output

- Green rectangle appears around moving objects.
- "MOTION DETECTED!" message is displayed.
- Alarm sound is played when movement is detected.

---

## 🎯 Applications

- Home Security
- Office Surveillance
- Intruder Detection
- Warehouse Monitoring
- Smart Surveillance Systems

---

## 🚀 Future Improvements

- Save intruder photos automatically
- Record video during motion detection
- Email notifications
- Face Recognition Integration
- AI-based Human Detection using YOLO
- Cloud Storage Support

---

## 👨‍💻 Author

Karan Raj

B.Tech CSE (AI & ML)

---

## 📄 License

This project is open-source and available under the MIT License.
