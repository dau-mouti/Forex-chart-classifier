# Forex Chart Classification Using CNN

A deep learning model for **Buy/Sell prediction** based on Forex candlestick chart images using **CNNs and Transfer Learning (ResNet50)**.

---

## Overview

This project uses a Convolutional Neural Network (CNN) and transfer learning with ResNet50 to classify Forex chart images into **Buy** or **Sell** signals. It is deployed as a simple web app for real-time predictions.

---

##  Key Features

-  CNN-based image classification with ResNet50
-  Precision: **0.77 (Buy)**, **0.73 (Sell)**
-  Deployed as a web application (Gradio)
-  Uses candlestick charts with SMA & EMA overlays
-  Clean, labeled dataset (not included in repo)

---

## 📁 Project Structure

/model/         → trained .h5 model (external link)
📒 /notebooks/  → training and evaluation notebooks
predict.py      → script for running predictions
app.py          → Gradio UI app
README.md       → project documentation

---

## ⚙️ How to Run

1. Clone this repository  
   `git clone https://github.com/dau-mouti/Forex-chart-classifier.git`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the app  
   `python app.py`

---

## Demo

Try the deployed version here:  
[Live Demo (Gradio)](https://702fa5f169d1637742.gradio.live)

---

## Model File (.h5)

 contact for the model

---

## How to Use the Model

1. Upload a Forex chart image (with SMA/EMA).
2. Run the app or `predict.py`.
3. Get a **Buy/Sell** prediction with **confidence score**.

---

## Key Technologies

- Python
- TensorFlow & Keras
- ResNet50 (Transfer Learning)
- Gradio (Web UI)

---

## Contact

📧 Reach out for the dataset or collaboration:
`daumouti@gmail.com` | [GitHub](https://github.com/dau-mouti)

---
