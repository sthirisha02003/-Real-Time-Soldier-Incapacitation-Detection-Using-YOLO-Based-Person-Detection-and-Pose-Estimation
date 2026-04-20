# 🚀 Real-Time Soldier Incapacitation Detection

An AI-powered real-time monitoring system that detects soldier incapacitation using YOLO-based human detection and pose estimation. The system processes video streams, extracts skeletal keypoints, and identifies abnormal postures such as collapse or immobility, generating instant alerts for faster rescue response in critical situations.

---

## 📌 Features

* ✅ YOLO-based human detection
* ✅ Pose estimation using skeletal keypoints
* ✅ Detects abnormal conditions (fall, collapse, immobility)
* ✅ Real-time video processing
* ✅ Alert system for emergency response

---

## 🛠️ Tech Stack

* Python
* OpenCV
* YOLO (You Only Look Once)
* Pose Estimation (MediaPipe / OpenPose)

---

## 📂 Project Structure

```
├── TERM_PAPER.ipynb     # Main implementation
├── README.md            # Project documentation
```

---

## ⚙️ How It Works

1. Capture video stream (camera/video input)
2. Detect humans using YOLO
3. Extract body keypoints using pose estimation
4. Analyze posture for abnormalities
5. Trigger alert if incapacitation is detected

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

## 📈 Future Improvements

* 🔹 Multi-AI system integration
* 🔹 Edge device deployment (Raspberry Pi, Jetson)
* 🔹 Improved accuracy using deep learning models
* 🔹 Integration with IoT-based alert systems

---

## 📜 License

This project is for academic and research purposes.
