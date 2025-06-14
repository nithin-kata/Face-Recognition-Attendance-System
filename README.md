# Face-Recognition-Attendance-System

A Python-based attendance system that uses face recognition to automate student attendance marking. The system allows registration, face image capture, training, real-time attendance, and data management using a user-friendly Tkinter GUI.

## 🚀 Features

- Register new students with ID, name, and department
- Capture face images via webcam
- Train a face recognition model (LBPH)
- Mark attendance by recognizing faces in real-time
- View attendance records and registered student details
- Delete individual student data from the system (images, records, etc.)
- Responsive GUI using Tkinter

## 🧰 Tech Stack

Python 3.10
OpenCV – For image capture and face recognition
Tkinter – GUI frontend
Pandas – CSV and data handling
NumPy – Numerical operations
Pillow (PIL) – Image management
OS / shutil – File system tasks

## 📁 Project Structure

FaceRecognitionAttendance/
├── Attendance/              # Stores daily attendance CSV files
├── StudentDetails/          # Stores student registration data
├── TrainingImage/           # Captured face images
├── TrainingImageLabel/      # Trained model and password file
├── haarcascade_frontalface_default.xml  # Haar Cascade for face detection
├── main.py                  # Main application script
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies


## ✅ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nithin-kata/FaceRecognitionAttendance.git
   cd FaceRecognitionAttendance
   
**2.Install dependencies:**

Install All the modules mentioned below 
pip install tk-tools
pip install opencv-contrib-python
pip install datetime
pip install pytest-shutil
pip install python-csv
pip install numpy
pip install pillow 
pip install pandas
pip install times

**3.Run the application**:

bash
Copy
Edit
python main.py

**📷 Image Capture Info**

By default, 71 images are captured per student for better model accuracy.
You can modify this count inside TakeImages() in main.py.
A minimum of 30–50 varied images is recommended for best results.

**🧹 Delete Functionality**
You can delete a student's data completely (images, records, and CSV entry) with one click using the GUI.

**🔐 Face Recognition Model**
Uses OpenCV's LBPH (Local Binary Patterns Histograms) algorithm.
Model is trained using images in TrainingImage/ and saved as TrainingImageLabel/Trainner.yml.

**🙌 Contributions**
Contributions, suggestions, and issues are welcome. Please fork the repo and create a pull request.

**📧 Contact**
For any queries, email: nithinkata29@gmail.com

**📄 License**
MIT License – free to use and modify.


