# Bicep-Curl-Counter-OpenCV
A real-time Bicep Curl Counter that uses Pose Estimation with MediaPipe and OpenCV to detect arm movements, calculate joint angles, and count repetitions accurately. This project can be used for fitness tracking and exercise monitoring applications.

📌 Features
✅ Real-time Pose Detection using MediaPipe
✅ Bicep Curl Angle Calculation with vector math
✅ Automatic Rep Counting
✅ Lightweight and works on CPU

🛠️ Tech Stack
Python 3.x
OpenCV – Image processing & webcam handling
MediaPipe – Pose estimation
NumPy – Mathematical calculations

📂 Project Structure
Bicep-Curl-Counter-OpenCV-MediaPipe/
│── bicep_curl_counter.py   # Main project code
│── requirements.txt        # Python dependencies
│── README.md               # Project documentation

📦 Installation
1️⃣ Clone the Repository
git clone https://github.com/ShivangGit123/Bicep-Curl-Counter-OpenCV-MediaPipe.git
cd Bicep-Curl-Counter-OpenCV-MediaPipe
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Program
python bicep_curl_counter.py


📊 How It Works
Pose Detection: MediaPipe detects body landmarks in each video frame.
Angle Calculation: The angle between the shoulder, elbow, and wrist is computed using trigonometry.
Rep Counting: The program detects upward and downward motion patterns to count repetitions.
Live Feedback: The webcam feed displays the current angle, rep count, and exercise stage (Up/Down).

📌 Example Use Case
This project can be integrated into:
🏋️ Fitness Tracking Apps
📹 Workout Recording Tools
🤖 AI Personal Trainers
