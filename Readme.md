# 🔥 Real-Time Fire & Smoke Detection

A real-time fire and smoke detection system using computer vision and deep learning. This tool is designed to monitor live video streams and promptly detect fire or smoke to help prevent disasters.

## 🚀 Features

- Real-time detection of **fire** and **smoke**  
- Uses pre-trained CNN or custom-trained models  
- Alerts via sound, logging, or messaging  
- Visual overlays with bounding boxes  
- Optional Flask app for browser-based monitoring

## 🧰 Tech Stack

- Python  
- OpenCV  
- TensorFlow or PyTorch  
- NumPy  
- (Optional) Flask for web dashboard  
- (Optional) Twilio/SMTP for alerting

## 📁 Project Structure

```
fire-smoke-detection/
├── models/                 # Trained models for fire and smoke
├── videos/                 # Demo videos or camera feeds
├── detect.py               # Main script for detection
├── utils.py                # Utility functions
├── app.py                  # Flask app (optional)
├── requirements.txt        # Dependencies
└── README.md
```

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/fire-smoke-detection.git
cd fire-smoke-detection
pip install -r requirements.txt
```

## 🎯 Usage

Run detection on webcam or video file:

```bash
python detect.py --source 0         # For webcam
python detect.py --source videos/test.mp4   # For a video file
```

## 🧠 Model Training (Optional)

You can train your own model using datasets like:
- [FIRESMOKE Dataset](https://github.com/lingchen233/FIRESMOKE-Database)
- Custom fire/smoke image sets

## 📬 Alerts

Configure email or SMS alerts in `utils.py` or integrate with platforms like Twilio or SMTP.
