# 🧍‍♂️ AI Posture Assistant

An AI-based posture detection system that analyzes human body posture using computer vision and provides feedback to improve sitting habits.

---

## 📌 Project Overview

AI Posture Assistant uses pose estimation to detect body landmarks and calculate neck angle.  
Based on the calculated angle, it determines whether the person is:

- ✅ Maintaining Good Posture  
- ❌ Slouching  

It then provides corrective suggestions to improve posture.

---

## 🛠️ Technologies Used

- Python  
- MediaPipe  
- OpenCV  
- NumPy  
- Matplotlib  
- Requests  

---

## 🧠 How It Works

1. The system loads an image.
2. MediaPipe detects body landmarks.
3. Neck angle is calculated using shoulder, ear, and hip points.
4. If angle < 150° → Slouching detected.
5. Otherwise → Good posture detected.

---

## 🚀 Features

- Real-time pose detection  
- Neck angle calculation  
- Posture classification  
- Corrective suggestion output  
- Landmark visualization  

---

## 📂 Project Structure
AI-Posture-Assistant/
│── AI_Posture_Assistant.ipynb
│── README.md


---

## ▶️ How to Run

### 1️⃣ Install Required Libraries

```bash
pip install mediapipe==0.10.20 opencv-python numpy matplotlib requests

2️⃣ Run the Notebook

Google Colab

Jupyter Notebook

📷 Sample Output
Neck Angle: 142.35°
Posture: Slouching ❌
Suggestion: Sit straight & pull shoulders back

🎯 Applications

Students

Office employees

Work-from-home professionals

Ergonomic health monitoring

👩‍💻 Author

K M Mythri Gowda
B.Tech Student


