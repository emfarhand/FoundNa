# 📚 FoundNa – Animal Recognition App

FoundNa is a **machine learning-powered mobile application** that identifies animals in real time.  
This project was built as part of the **Bangkit 2023 Capstone Project** and demonstrates **image classification** using a lightweight and optimized MobileNetV2 model, deployed with **TensorFlow Lite** for on-device inference.

---

## ✨ Features

✅ **Real-Time Animal Detection** – Capture or upload images and get instant classification results.  
✅ **Lightweight & Fast** – Uses MobileNetV2 + TensorFlow Lite for efficient inference on mobile devices.  
✅ **Cloud-Ready Pipeline** – Model trained on Google Cloud Platform for scalability.  
✅ **High Accuracy** – Achieved ~95% classification accuracy on validation data.

---

## 🛠️ Tech Stack

- **Model:** MobileNetV2 (transfer learning)
- **Frameworks:** TensorFlow, TensorFlow Lite
- **Language:** Python
- **Platform:** Google Colab & Google Cloud
- **Deployment:** TFLite for Android Mobile App
- **Visualization:** Matplotlib, Seaborn (for training analysis)

---

## ⚙️ How to Run

1. **Clone this repository**

```bash
git clone https://github.com/emfarhand/FoundNa.git
cd FoundNa

```

2. **Open the training notebook**

Use Google Colab or Jupyter Notebook to open Script_Model_FoundNa.ipynb.

Follow the steps inside to preprocess dataset, train, and export the model.

3. **Export to TensorFlow Lite**

The notebook contains code to convert the trained model to .tflite format.

Deploy the .tflite model to your Android app.

## 📬 Contact

Email: farhanlangsa003@gmail.com
LinkedIn: linkedin.com/in/emfarhand
