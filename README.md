
# 🔍 Simple YOLOv8 Object Detection

A beginner-friendly project using YOLOv8 and OpenCV to perform real-time object detection through your webcam.

---

## 📁 Project Structure

```
simple-yolo-project/
├── detect.py             # Main script to run object detection
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## ✅ Features

- Real-time object detection from webcam
- Uses pre-trained YOLOv8n model (`yolov8n.pt`)
- Lightweight and easy to run on any system

---

## ⚙️ Setup Instructions

### 1️⃣ Clone or Download the Repo
```bash
git clone https://github.com/PhaniMax/simple-yolo-project/tree/main
cd simple-yolo-project
```

### 2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate  # Windows
# OR
source venv/bin/activate  # macOS/Linux
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Object Detection
```bash
python detect.py
```

> Press `q` to quit the webcam window.

---

## 🧠 Model Info

- This project uses Ultralytics' **YOLOv8n** model (nano version) for fast detection.
- The model is automatically downloaded from Ultralytics if not found locally.

---

## 📌 Notes

- Make sure your internet is on during the first run to download `yolov8n.pt`.
- You can switch to other models like `yolov8s.pt`, `yolov8m.pt`, etc., by modifying:
  ```python
  model = YOLO("yolov8n.pt")
  ```

---

## 🙌 Credits

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- [OpenCV](https://opencv.org/)

---

## 📷 Sample Output

You’ll see bounding boxes drawn in real-time on webcam video feed like this:

```
[person] 98%
[phone] 93%
```

---

## 📤 License

This project is open-source and free to use for learning and educational purposes.
