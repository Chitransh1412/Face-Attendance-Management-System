# Face Attendance Management System (FRAMS)

A smart, secure, and efficient facial recognition-based attendance management system that eliminates the need for manual or card-based check-ins. FRAMS leverages deep learning and computer vision to automate the attendance process with high accuracy and real-time verification.

---

## 🚀 Features

- 🔒 Secure biometric-based attendance system
- 🤖 Real-time face detection & recognition
- 📸 Live webcam capture for identification
- 📊 Attendance records stored securely in a database
- 📂 Easy-to-use interface for marking and viewing attendance
- 📁 Monthly report generation
- ⚡ Fast, accurate, and proxy-resistant

---

## 🧠 Tech Stack

- **Frontend:** Tkinter (Python GUI)
- **Backend:** Python
- **Libraries & Tools:**  
  - OpenCV  
  - face_recognition  
  - NumPy  
  - Pandas  
  - SQLite (for storing attendance data)  
- **Machine Learning:**  
  - Deep Learning-based Face Recognition using pre-trained models

---

## 📷 System Workflow

1. **Face Capture:** The system captures images of individuals using a webcam.
2. **Face Encoding:** It encodes each face using deep learning features.
3. **Recognition:** On running, it compares real-time faces to the stored encodings.
4. **Attendance Logging:** If matched, attendance is marked with timestamp.
5. **Reports:** Admin can export attendance logs to Excel or other formats.

---

## 📦 Installation

> Make sure Python 3.8+ is installed on your system.

1. **Clone the repository**
   ```bash
   git clone https://github.com/Chitransh1412/Face-Attendance-Management-System.git
   cd Face-Attendance-Management-System
