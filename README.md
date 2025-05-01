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

- **Python 3**
- **OpenCV** – For image capture and face detection/recognition
- **Tkinter** – For the GUI
- **Pandas** – For CSV and data handling
- **NumPy** – For numerical processing
- **OS / shutil** – For file system operations

## 📁 Project Structure

FaceRecognitionAttendance/ │ ├── dataset/ # Captured face images ├── trainer/ # Trained model file (trainer.yml) ├── attendance/ # Attendance CSV records ├── studentdetails.csv # Student registration info ├── trainingImageLabel/ # Used during training ├── main.py # Main application script ├── README.md # Project documentation └── requirements.txt # Python dependencies

## ✅ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/FaceRecognitionAttendance.git
   cd FaceRecognitionAttendance
   
2.Install dependencies:
pip install -r requirements.txt

3.Run the application:

bash
Copy
Edit
python main.py

📷 Image Capture Info
By default, 101 images are captured per student for better training accuracy.

You can adjust this number in the code if needed.

A minimum of 30–50 varied images is recommended.

🧹 Delete Functionality
You can delete a student's data completely (images, records, and CSV entry) with one click using the GUI.

🔐 Face Recognition Model
Uses OpenCV's LBPH (Local Binary Patterns Histograms) algorithm.

Model is trained on images in the dataset/ folder and saved as trainer.yml.

🙌 Contributions
Contributions, suggestions, and issues are welcome. Please fork the repo and create a pull request.

📄 License
MIT License – free to use and modify.


