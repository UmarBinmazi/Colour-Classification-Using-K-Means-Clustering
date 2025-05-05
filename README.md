# 🎨 Color Detection App

[![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-ff4b4b?logo=streamlit&logoColor=white)](https://streamlit.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)

An interactive web app to detect **dominant colors** in an image using **K-Means Clustering**.

---

## 📌 Features

- 📤 Upload any image
- 🎯 Detect dominant colors using **K-Means Clustering**
- 📊 View:
  - Closest CSS3 color names
  - Hex codes
  - Color usage percentages

---

## 🧠 How It Works

1. Image is resized and preprocessed.
2. **K-Means Clustering** groups pixels into color clusters.
3. Optimal number of clusters is chosen using the **elbow method**.
4. Each cluster center is:
   - Converted to hexadecimal
   - Mapped to the nearest CSS3 color name
   - Calculated for percentage share in the image

---

## 📸 Example Use Case

Upload a photo of a **sunset**, and the app will return dominant colors like:
- 🟠 Orange
- 💗 Pink
- 💜 Purple  
with their **hex codes** and **percentages** in the image.

---

## 🚀 Getting Started

### ✅ Prerequisites
Make sure you have Python 3.8+ installed. Then install dependencies:

```bash
pip install -r requirements.txt
