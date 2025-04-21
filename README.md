# Real-Time Face Detection

A simple and efficient real-time face detection system built using OpenCV and deep learning. This project detects and highlights faces in images and video streams.

## ✨ Features

- Real-time face detection from live video or images
- Uses OpenCV’s pre-trained Haar Cascade classifier or deep learning models
- Easy-to-use and fast
- Can be extended for face recognition or tracking

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- NumPy
- Haar Cascade Classifier (for face detection)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/face-detection.git
cd face-detection
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Application
For real-time face detection with webcam:

bash
Copy
Edit
python face_detect.py
For detecting faces from a static image:

python detect_from_image.py --image your_image.jpg
📁 Project Structure

face-detection/
│
├── face_detect.py           # Main script for real-time face detection
├── detect_from_image.py     # Script for detecting faces from an image
├── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade file
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation


🤖 How It Works
Haar Cascade Classifier detects faces using pre-trained features in real-time.

OpenCV captures frames from the webcam or image file, processes them, and applies the face detection algorithm.

Detected faces are highlighted with rectangles for visual feedback.

License: This project is licensed under the MIT License. See the LICENSE file for more details.
