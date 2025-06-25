# chicken-weight-estimation
A computer vision project using YOLOv8 to estimate chicken weight and activity from images.
# 🐔 Chicken Weight Estimation Using Computer Vision (YOLOv8)

This project uses a YOLOv8-based object detection model to classify chicken behavior (`eat-drink`, `moving`, `rest`) and estimate their weight from images using bounding box dimensions.

---

## 📌 Problem Statement

Estimate the **weight of chickens** using images and their detected size and posture. This is especially helpful in livestock automation and smart poultry farms.

---

## 🧠 Project Highlights

- Trained YOLOv8 on a Roboflow dataset of chicken activities
- Predicted activities from test images
- Estimated weight using bounding box area
- Used GPU-accelerated Google Colab environment
- Achieved **84% mAP@0.5** on validation

---

## 🧰 Tech Stack

- Python, Google Colab
- YOLOv8 (Ultralytics)
- Roboflow
- OpenCV, Matplotlib, PyTorch

---

## 📈 Sample Results

![](runs/detect/predict/sample.jpg)  <!-- Replace with your output sample if available -->

---

## 📁 Files

- `chicken_weight_estimator.ipynb` – Full Colab notebook with code, comments, results
- `README.md` – Project summary

---

## 👤 Author

**S. Tejash**  
📧 singaladevitejash@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/s-tejash-96b70a262) | [GitHub](https://github.com/Tejash213)

---

## ✅ License

This project is based on public datasets and open-source tools. Free to use with credit.

