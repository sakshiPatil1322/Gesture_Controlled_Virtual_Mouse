# Gesture Controlled Virtual Mouse 🎯


Gesture Controlled Virtual Mouse simplifies human-computer interaction using **hand gestures and voice commands**. The system performs all major input operations virtually — such as mouse control, scrolling, clicking, and even system automation — without direct physical contact.  

This project utilizes **MediaPipe**, **OpenCV**, and **PyAutoGUI** for gesture tracking. It combines **Computer Vision** and **Machine Learning** to deliver a smooth, contactless experience — all running on a standard webcam without extra hardware.

---

## 🚀 Features

### 🖐️ Gesture Recognition
- **Move Cursor** – Control the pointer using hand movements.  
- **Left / Right / Double Click** – Perform clicks using specific hand gestures.  
- **Scroll Control** – Vertical and horizontal scrolling through dynamic pinch gestures.  
- **Drag & Drop** – Pick up and move items with gesture-based control.  
- **Volume & Brightness Control** – Adjust using distance-based pinch movements.  
- **Multiple Item Selection** – Select multiple files or icons effortlessly.  



## ⚙️ System Requirements
- **Operating System:** Windows 10 or later  
- **Python Version:** 3.6 – 3.8.5  
- **Camera:** Built-in or external webcam  
- **Microphone:** For voice command input  

---

## 🧩 Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/sakshiPatil1322/Gesture_Controlled_Virtual_Mouse.git

Step 2: Create a Virtual Environment
conda create --name gest python=3.8.5

Step 3: Activate the Environment
conda activate gest

Step 4: Install Dependencies
pip install -r requirements.txt

Step 5: Install Additional Libraries
conda install PyAudio
conda install pywin32

Step 6: Navigate to the Source Folder
cd Gesture-Controlled-Virtual-Mouse/src

Step 7: Run the Project
python Gesture_Controller.py




🧠 Technologies Used

Python 3.8.5

OpenCV – Real-time image and gesture processing

MediaPipe – Hand landmark detection model

PyAutoGUI – Cursor and system automation

SpeechRecognition – Voice command recognition

Pycaw & PyWin32 – Volume and system control

Screen Brightness Control – Adjust display brightness dynamically