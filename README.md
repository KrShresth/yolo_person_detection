# YOLO Person Detection 🧍‍♂️ | YOLOv8

This project implements a YOLOv8-based object detection pipeline to identify persons in images. The entire workflow—from data collection to evaluation—was conducted using Python in Google Colab.

---

## 📌 Problem Statement

Detect people in images using a robust object detection system based on YOLOv8. The steps included:

1. **Collecting a dataset** of 100+ images containing people under different conditions.
2. **Annotating** the dataset using [LabelImg](https://github.com/tzutalin/labelImg) in YOLO format.
3. **Applying a YOLOv8 model** to perform object detection on the dataset.
4. **Evaluating performance** using metrics such as Precision, Recall, F1 Score, and mAP@50.

---

## 📁 Project Structure

```
Yolo_Person_Detection/
│
├── data/                   # Dataset and labels
├── predictions/            # YOLOv8 predicted outputs
├── Yolo_Assignment.ipynb   # Main notebook
└── README.md               # This file
```

---

## 🛠 Tools & Technologies

- Python
- [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)
- Google Colab
- LabelImg for annotation
- TorchMetrics for evaluation
- OpenCV for image visualization

---

## 📊 Evaluation Metrics

The performance of the model is measured using:
- **Precision**
- **Recall**
- **F1-Score**
- **mAP@50** (mean Average Precision at IoU threshold 0.5)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/KrShresth/yolo_person_detection.git
   cd yolo_person_detection
   ```

2. Open the notebook `Yolo_Assignment.ipynb` in **Google Colab**.

3. Make sure your data is annotated in YOLO format and mounted from Google Drive.

4. Run the notebook sequentially to train and evaluate the model.

---

## ✍️ Author

**Shresth Raj**  
If you find this project helpful, feel free to ⭐️ the repository!
