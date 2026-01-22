#  Burglary Activity Detector using AI & Pose Estimation

A **real-time AI-based burglary detection system** that uses **human pose estimation** to identify suspicious activities through a webcam and raises instant alerts. This project is designed for **smart surveillance and security monitoring systems**.

---

##  Project Overview

Traditional CCTV systems require continuous human monitoring, which is inefficient and error-prone. This project automates the detection of **suspicious human activities** such as burglary-related movements by analyzing **body posture and motion patterns** in real time.

The system uses a **Teachable Machine Pose Model** integrated with **TensorFlow.js** to classify human actions and trigger alerts when abnormal behavior is detected.

---

##  Key Features

-  Real-time webcam-based monitoring  
-  Human pose estimation using PoseNet  
-  AI-based activity classification  
-  Automatic alert on suspicious activity  
-  Audio alarm for immediate attention  
-  Attractive and responsive UI  
-  Reduced false alerts using confidence threshold & frame validation  

---

##  How It Works

1. Webcam captures live video frames  
2. PoseNet extracts human body keypoints  
3. Trained Teachable Machine model predicts activity class  
4. System checks confidence and stability across frames  
5. Alert is triggered if suspicious activity is confirmed  

---

##  Technologies Used

| Category | Technology |
|--------|------------|
| Frontend | HTML, CSS, JavaScript |
| AI / ML | Teachable Machine (Pose Model) |
| Pose Estimation | PoseNet |
| ML Framework | TensorFlow.js |
| Real-Time Processing | Webcam API |
| Visualization | HTML5 Canvas |
| Alert System | JavaScript Audio API |

---

##  Model Details

- **Model Type:** Pose Classification  
- **Trained Using:** Google Teachable Machine  
- **Input:** Human body keypoints  
- **Output:** Activity class probabilities  
- **Confidence Threshold:** ≥ 98%  
- **Frame Validation:** 15 consecutive frames  

---

Burglary-Activity-Detector/
│
├── index.html # Main application file
└── README.md # Project documentation


---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Burglary-Activity-Detector.git

2. Open the project folder

3. Open index.html in a modern browser (Chrome recommended)

4.Allow webcam access

5. Click Start Detection



## Future Enhancements

 - Backend integration (Firebase / Server alerts)

 - Mobile compatibility

 - Activity logging & evidence capture

 - Integration with smart city surveillance systems

 - Improved model accuracy with more training data

##  Author

Chippada Mahitha
B.Tech – Artificial Intelligence & Data Science



