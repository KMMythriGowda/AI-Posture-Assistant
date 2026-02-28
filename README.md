**AI Posture Assistant**

An AI-based posture detection system that analyzes human body posture using computer vision and provides feedback to improve sitting habits.

**Project Overview**

AI Posture Assistant uses pose estimation to detect body landmarks and calculate neck angle.
Based on the angle, it determines whether the person is:

✅ Maintaining good posture

❌ Slouching

It then gives corrective suggestions.

**Technologies Used**

Python

MediaPipe

OpenCV

NumPy

Matplotlib

Requests

**How It Works**

The system loads an image.

MediaPipe detects body landmarks.

Neck angle is calculated using shoulder, ear, and hip points.

If angle < 150° → Slouching detected.

Otherwise → Good posture detected.

**Features**

Real-time pose detection

Neck angle calculation

Posture classification

Corrective suggestion output

Landmark visualization

**Project Structure**
AI-Posture-Assistant/
│── AI_Posture_Assistant.ipynb
│── README.md
▶️ How to Run

**Install required libraries:**

pip install mediapipe==0.10.20 opencv-python numpy matplotlib requests

**Run the notebook in:**

Google Colab

Jupyter Notebook

**Sample Output**

Neck Angle: 142.35°

Posture: Slouching ❌

Suggestion: Sit straight & pull shoulders back

**Applications**

Students

Office employees

Work-from-home professionals

Ergonomic health monitoring

**Author**
K M Mythri Gowda
B.Tech Student
