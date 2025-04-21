# ♟️ Chessboard Analysis using Computer Vision

## 📌 Overview

This project analyzes an image of a chessboard and accurately counts the number of **black and white squares** using computer vision techniques. The solution is designed to handle:

- Different orientations and angles
- Lighting variations and shadows
- Minor image imperfections or distortions

It has been implemented entirely in **Python using OpenCV**, within a **Google Colab Notebook** for ease of development and demonstration.

---

## 🧠 Objective

The goal of this project is to demonstrate problem-solving, creativity, and technical expertise in **AI and Computer Vision** by building a robust square detection and classification algorithm.

---

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## 📸 Sample Input

- Uploaded images of chessboards (e.g., `chessboard4.jpg`)  
- Supports both **clear** and **angled or lit** chessboards (future enhancements can extend this further)

---

## 🔍 Approach

### 1. **Image Acquisition**
- Chessboard images are either publicly sourced or captured manually
- Images are uploaded directly to the Colab environment

### 2. **Preprocessing**
- Conversion to grayscale
- Image resizing for uniform analysis
- Normalization of pixel values

### 3. **Square Detection**
- Divide the image into an 8x8 grid (64 squares)
- For each square, compute average brightness
- Classify square as:
  - **Black** if average pixel intensity < 127
  - **White** otherwise
- Draw color-coded rectangles for visualization

### 4. **Validation**
- Count the number of black and white squares
- Display annotated image to verify correct square detection

---

## ✅ Results

For a clean 8x8 chessboard image:

```bash
Black squares: 32
White squares: 32

<img width="1440" alt="Screenshot 2025-04-21 at 5 31 32 PM" src="https://github.com/user-attachments/assets/3ab31e39-e56a-42c5-8b80-609caff8e364" />
<img width="1440" alt="Screenshot 2025-04-21 at 5 31 28 PM" src="https://github.com/user-attachments/assets/ba12bb20-cc60-4236-8658-ec16a4c9bb72" />
