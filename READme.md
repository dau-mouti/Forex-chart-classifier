# Forex Chart Classification Using CNN

This project uses a Convolutional Neural Network (EfficientNet) to classify candlestick chart images into **Buy** or **Sell** signals.

##  Key Features
- CNN-based image classification
- Precision: 0.77 (Buy), 0.73 (Sell)
- Deployed as a web application
- Clean, labeled dataset with chart overlays (SMA, EMA)

##  Project Structure
- `/model/` - trained `.h5` model
- `/notebooks/` - training and testing notebooks
- `/images/` - sample charts, confusion matrix, UI screenshots

##  How to Run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run notebook or UI script

##  Demo
https://702fa5f169d1637742.gradio.live

contact developer/me for the dataset. 

### Model File (.h5)

Due to GitHub's 100MB file size limit, the trained model file is hosted externally:

🔗 [Download Trained Model (.h5)](https://drive.google.com/file/d/1XGMSDiAeas65lmKnIDA_4lM2QKViS9up/view?usp=drive_link)

---

###  How to Use

1. Upload a Forex chart image (with moving averages).
2. Run `predict.py` to get a Buy/Sell prediction and confidence score.

---

### Key Technologies

- Python
- TensorFlow/Keras
- ResNet50 (Transfer Learning)
