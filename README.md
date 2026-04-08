# 🧪 Microorganism Detection System

## 📌 Project Overview

This project presents a complete end-to-end system for the detection of microorganisms from blood smear images. It combines hardware, embedded systems, artificial intelligence, and application development into a unified solution.

The system is designed to:
- Capture high-quality images using a custom-built optical device
- Process and analyze images using machine learning models
- Provide results through a user-friendly web and mobile interface

---

## ⚙️ System Architecture

The project is composed of three main components:

### 1. 🔬 Image Acquisition Device
- Custom-built hardware integrating:
  - Camera module
  - Optical lenses
- Designed to capture detailed blood smear images suitable for analysis

### 2. 🧠 AI & Embedded System
- Hosted on a **Raspberry Pi 5**
- Responsibilities:
  - Image preprocessing
  - Running the trained AI model
  - Performing microorganism detection
- Built using:
  - Python
  - Jupyter Notebooks
  - Machine Learning / Computer Vision techniques

### 3. 🌐 Web & Mobile Application
- Provides:
  - User interface for interaction
  - Image upload / capture
  - Visualization of results
- Communicates directly with the Raspberry Pi

---

## 📂 Rdataset
https://datasetcatalog.nlm.nih.gov/dataset?q=0001491007 for bacteriology




---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

pip install -r requirements.txt

jupyter notebook
