# 📌 CIFAR-10 Image Classification

A **Convolutional Neural Network (CNN)** model to classify images from the **CIFAR-10 dataset**, which consists of 10 categories: 

🚗 Automobile | 🏠 House | 🐶 Dog | 🐱 Cat | 🛩 Airplane | 🦌 Deer | 🐸 Frog | 🐴 Horse | 🚢 Ship | 🚚 Truck

---

## 📂 Dataset
The **CIFAR-10 dataset** consists of **60,000 32x32 color images** in 10 classes, with **6,000 images per class**. It is available for download at:

🔗 [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

---

## 🛠 Tech Stack
- **Python** 🐍
- **TensorFlow** 🤖
- **NumPy** 📊
- **Pandas** 🏷
- **Matplotlib & Seaborn** 📈

---

## 🚀 Model Architecture
The CNN model consists of **4 layers** with the following components:
✅ **Conv2D** (Convolutional Layers)
✅ **MaxPooling2D** (Pooling Layers)
✅ **BatchNormalization** (Normalization Layers)
✅ **Flatten** (Feature Extraction)
✅ **Dropout** (Regularization)
✅ **Dense** (Fully Connected Layers)

🔧 **Optimization:** Adam (Learning Rate = 0.001) | **Loss Function:** Categorical Crossentropy | **Evaluation Metric:** Accuracy

---

## 🚀 Uploading the Model
Once the model is trained, you can save and upload it for later use:

1️⃣ Save the trained model:
```python
model.save("Cifar-10.h5")
```

2️⃣ Upload the saved model to your desired storage or deployment platform.

3️⃣ Load the model when needed:
```python
from tensorflow.keras.models import load_model
model = load_model("Cifar-10.h5")
```

---

## 📊 Results
The model achieves **89.6% accuracy** on the CIFAR-10 dataset.

---

## 🤝 Collaboration
Feel free to contact me if you have ideas for improving this project or want to collaborate on something similar. Let's create something amazing together! 🚀

---

## 📜 License
This project is licensed under the **MIT License**.

📩 *For queries, reach out at* [aadvikmazumdar@gmail.com](mailto:aadvikmazumdar@gmail.com)
