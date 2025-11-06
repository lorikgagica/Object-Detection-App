# 🦾 YOLOv5 Object Detection Python Script

This project demonstrates **object detection in images and real-time webcam video using the state-of-the-art YOLOv5 deep learning model**. You can choose to detect objects in a static image or through your webcam—results are instantly visualized!

---

## 🚀 Features

- **Detects objects in any image file:**  
  Draws bounding boxes and labels for things like people, cars, animals, etc.
- **Real-time detection from webcam:**  
  Sees and processes a live video feed, drawing boxes on detected objects as you move.
- **Uses YOLOv5s (small, fast, accurate pre-trained model)** from Ultralytics.

---

## 📦 Requirements

Install with pip before running:
`pip install torch torchvision torchaudio opencv-python numpy`
YOLOv5 will be automatically downloaded and loaded via PyTorch's `torch.hub`.

**You need:**
- Python 3.7+
- A computer with a webcam for live demos.

---

## 🛠 How to Use

1. Save the script as `object.py`
2. Open a terminal in the same folder
3. Type: `python object.py`
4. Follow on-screen prompts:
- Enter `1` to detect objects in your own image (type the image’s file path)
- Enter `2` for real-time webcam detection (press `q` to quit the live video)

---

## 💡 Example Workflow

Choose an option:

1. Detect objects in an image
2. Real-time object detection from webcam
Enter 1 or 2: 1
Enter image path: sample.jpg
(Detected objects will be visualized in a pop-up window!)

---

## 🗜️ How it Works

- Loads YOLOv5s from the official Ultralytics repo via PyTorch Hub
- For images: runs detection and displays bounding boxes/labels
- For webcam: continually processes video, overlaying boxes in real time
- Keyboard shortcut `q` closes webcam window

---

## 🎓 Learning Value

- See how modern deep learning models are used for object detection in the real world
- Practice basic image and video processing with OpenCV and PyTorch
- Copy and extend for your own ML, AI, or computer vision projects!

---

## 📜 License

MIT — free for personal, educational, and research use.

---

> Detect anything, anywhere—in images or live video—with less than 50 lines of Python code!
