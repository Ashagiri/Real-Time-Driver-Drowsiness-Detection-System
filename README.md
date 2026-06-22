# 🚗 Real-Time Driver Drowsiness Detection System

A real-time driver drowsiness detection system that uses computer vision and deep learning techniques to monitor the driver's eye movements and facial features. The system detects signs of fatigue and provides immediate alerts to help prevent road accidents. A Django-based web application enables real-time monitoring, event logging, and dashboard access for administrators, drivers, and vehicle owners.
a common major road accidents in nepal.

# 📖 Overview:

Road accidents are a major public safety concern in Nepal. Driver fatigue and drowsiness are among the leading causes of accidents, especially on long-distance routes and highways. Due to limited access to affordable real-time monitoring systems, many fatigue-related incidents go undetected, resulting in injuries and loss of lives.

The Real-Time Driver Drowsiness Detection System aims to address this problem by continuously monitoring the driver's eye movements and facial features using computer vision techniques. When signs of drowsiness are detected, the system immediately generates alerts and records events through a Django-based web application, helping to prevent accidents and enhance road safety.

## 📌 Features:

* 👁️ Real-time eye and facial landmark detection
* 😴 Drowsiness detection using Eye Aspect Ratio (EAR)
* 🔔 Instant audio alerts when drowsiness is detected
* 📊 Event logging and alert history
* 🌐 Django-based web dashboard
* 👨‍💼 Separate Admin, Driver, and Vehicle Owner interfaces
* 📡 Real-time monitoring and reporting
* 💾 Database storage for detected events

## 🏗️ System Architecture:

The system follows a four-layer architecture:

1. **Hardware Layer**

   * Camera for capturing driver's face

2. **Processing Layer**

   * Face detection and facial landmark extraction
   * Drowsiness analysis using Eye Aspect Ratio (EAR)

3. **Communication Layer**

   * Wi-Fi and REST APIs for data transmission

4. **Application and Cloud Layer**

   * Django web application
   * Database storage and dashboard visualization

## 🛠️ Technologies Used:

* Python
* OpenCV
* Dlib
* NumPy
* SciPy
* Django
* HTML, CSS, JavaScript
* SQLite/MySQL
* REST API

## 📂 Project Structure

```text
Real-Time-Driver-Drowsiness-Detection-System/
│
├── detection/              # Drowsiness detection module
├── dashboard/              # Django web application
├── static/                 # CSS, JS, Images
├── templates/              # HTML templates
├── media/                  # Uploaded files
├── models/                 # Trained models
├── requirements.txt
├── manage.py
└── README.md
```

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Real-Time-Driver-Drowsiness-Detection-System.git
cd Real-Time-Driver-Drowsiness-Detection-System
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the Django server

```bash
python manage.py runserver
```

## 🚀 Usage

1. Start the application.
2. Enable the webcam.
3. The system continuously monitors the driver's eyes and facial expressions.
4. If drowsiness is detected, an alert is triggered.
5. Detection events are stored and displayed on the web dashboard.

## 📈 Future Enhancements

* Mobile application integration
* GPS tracking and vehicle monitoring
* SMS and email notifications
* Cloud-based analytics
* Support for multiple drivers
* Machine learning model optimization

