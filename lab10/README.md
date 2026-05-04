# Lab 10 — Image Segmentation and Feature Extraction

## 📘 Course Information

* **Course:** ARTI404 – Image Processing
* **College:** College of Computer Science and Information Technology
* **University:** Imam Abdulrahman Bin Faisal University

---

## 📌 Overview

This lab focuses on fundamental techniques in **image segmentation** and **feature extraction** using Python and OpenCV. The goal is to explore how images can be analyzed to detect edges, corners, and segmented regions.

The notebook includes both **demonstration examples** and an **assessment task**.

---

## 🎯 Objectives

* Understand edge detection techniques
* Extract important image features (corners)
* Apply different thresholding methods for segmentation
* Analyze image histograms
* Implement automatic threshold selection using Otsu’s method

---

## 🧪 Implemented Techniques

### 1. Canny Edge Detection

* Detects sharp intensity changes (edges)
* Produces thin and well-connected edges
* Function used: `cv2.Canny()`

---

### 2. Harris Corner Detection

* Identifies corner points in an image
* Useful for feature matching and tracking
* Function used: `cv2.cornerHarris()`

---

### 3. Simple (Global) Thresholding

* Uses a fixed threshold value (T)
* Converts grayscale image into binary image
* Function used: `cv2.threshold()`

---

### 4. Otsu’s Thresholding (Assessment Task)

* Automatically determines the optimal threshold value
* Assumes a bimodal histogram (foreground and background)
* Maximizes between-class variance
* Function used: `cv2.threshold(... + THRESH_OTSU)`

---

## 📊 Output

The notebook displays:

* Original images
* Processed results for each technique
* Histogram visualization (for Otsu’s method)
* Comparison between segmentation approaches

---

## 🛠️ Requirements

Make sure the following libraries are installed:

```bash
pip install opencv-python numpy matplotlib scikit-image
```

---

## ▶️ How to Run

1. Open the notebook in Jupyter Notebook or JupyterLab
2. Run cells sequentially
3. Observe outputs for each technique
4. Capture screenshots if required for submission

---

## 📈 Key Observations

* Canny produces clean and thin edges compared to other methods
* Harris successfully highlights corner points in textured regions
* Simple thresholding depends heavily on the chosen value
* Otsu’s method provides better segmentation automatically

---

## 🧾 Conclusion

This lab demonstrates essential image processing techniques used in real-world applications such as object detection, computer vision, and pattern recognition. Otsu’s thresholding proves to be an effective method for automatic image segmentation.

---

## 👨‍💻 Author

* **Student Name:** [Your Name]
* **Student ID:** [Your ID]

---

