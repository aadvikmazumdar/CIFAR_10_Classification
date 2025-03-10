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

## 🔧 Installation & Setup
1️⃣ Clone the repository:
```bash
 git clone https://github.com/yourusername/CIFAR-10-Classification.git
 cd CIFAR-10-Classification
```

2️⃣ Install dependencies:
```bash
 pip install -r requirements.txt
```

3️⃣ Run the training script:
```bash
 python train.py
```

4️⃣ Test the model:
```bash
 python test.py
```

---

## 📊 Results
The model achieves **89.6% accuracy** on the CIFAR-10 dataset. Below is a sample classification result:

![Sample Output](sample_output.png)

---

## 🤝 Collaboration
Feel free to contact me if you have ideas for improving this project or want to collaborate on something similar. Let's create something amazing together! 🚀

---

## 📜 License
This project is licensed under the **MIT License**.

📩 *For queries, reach out at* [your.email@example.com](mailto:your.email@example.com)

