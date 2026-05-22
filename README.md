🎨 Real-Time Color Detection using OpenCV
Python OpenCV License

A simple real-time computer vision project that detects a specific color (yellow by default) from a webcam feed using OpenCV and HSV color space filtering.

📸 Demo


🚀 Features
🎥 Real-time webcam capture
🎨 HSV-based color detection
🟩 Bounding box around detected objects
🧼 Noise-free mask visualization
⚡ Lightweight and fast
🧠 How It Works
Capture frames from webcam
Convert BGR → HSV color space
Define HSV range for target color
Generate binary mask using cv2.inRange()
Detect object using bounding box
Display results in real time
📂 Project Structure
CV-colorDetection/
│
├── main.py          # Main application (webcam + detection loop)
├── util.py          # HSV range utility function
├── assets/
│   └── demo.gif     # Demo preview (add your own)
└── README.md
🛠️ Installation
Clone the repository:

git clone https://github.com/your-username/CV-colorDetection.git
cd CV-colorDetection
Install dependencies:

pip install -r requirements.txt
📦 Requirements
opencv-python
numpy
pillow
▶️ Usage
Run the project:

python main.py
Press q to exit

Two windows will appear:

frame → live video with detection box
mask → binary color mask
🎯 Customization
Change the detected color in main.py:

yellow = [0, 255, 255]  # BGR format
⚠️ Notes
Detection depends on lighting conditions
HSV range tuning may be needed for different environments
Webcam must be accessible
🔮 Future Improvements
Multi-color tracking
Object centroid tracking (x, y coordinates)
Real-time HSV sliders
Robotics or automation integration
📜 License
This project is licensed under the MIT License.

⭐ Show Support
If you like this project, consider giving it a ⭐ on GitHub!
