# 🎨 Real-Time Color Detection using OpenCV

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A simple real-time computer vision project that detects a specific color (yellow by default) from a webcam feed using OpenCV and HSV color space filtering.

---

## 📸 Demo

![Demo](assets/demo.gif)

---

## 🚀 Features

* 🎥 Real-time webcam capture
* 🎨 HSV-based color detection
* 🟩 Bounding box around detected objects
* 🧼 Noise-free mask visualization
* ⚡ Lightweight and fast

---

## 🧠 How It Works

1. Capture frames from webcam
2. Convert BGR → HSV color space
3. Define HSV range for target color
4. Generate binary mask using `cv2.inRange()`
5. Detect object using bounding box
6. Display results in real time

---

## 📂 Project Structure

```
CV-colorDetection/
│
├── main.py          # Main application (webcam + detection loop)
├── util.py          # HSV range utility function
├── assets/
│   └── demo.gif     # Demo preview (add your own)
└── README.md
```

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/CV-colorDetection.git
cd CV-colorDetection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

```
opencv-python
numpy
pillow
```

---

## ▶️ Usage

Run the project:

```bash
python main.py
```

* Press **`q`** to exit
* Two windows will appear:

  * `frame` → live video with detection box
  * `mask` → binary color mask

---

## 🎯 Customization

Change the detected color in `main.py`:

```python
yellow = [0, 255, 255]  # BGR format
```

---

## ⚠️ Notes

* Detection depends on lighting conditions
* HSV range tuning may be needed for different environments
* Webcam must be accessible

---

## 🔮 Future Improvements

* Multi-color tracking
* Object centroid tracking (x, y coordinates)
* Real-time HSV sliders
* Robotics or automation integration

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Show Support

If you like this project, consider giving it a ⭐ on GitHub!
