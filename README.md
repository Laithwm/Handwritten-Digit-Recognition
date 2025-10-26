# 🧠 Handwritten Digit Recognition (MNIST)

Deep learning project that classifies handwritten digits (0–9) using neural networks and CNNs on the MNIST dataset.

---

## 📁 Project Structure
```text
Handwritten-Digit-Recognition/
├── data/
│   ├── mnist_train.csv
│   └── mnist_test.csv
├── notebooks/
│   └── handwritten_digit_recognition.ipynb
├── models/
│   └── mnist_cnn_model.h5
├── images/
│   ├── training_plot.png
|   ├── training_plot2.png
│   ├── confusion_matrix.png
│   └── predictions.png
└── README.md
```

---

## ⚙️ Setup
```bash
pip install pandas numpy matplotlib seaborn tensorflow scikit-learn
```

---

## 🚀 Run Notebook
```bash
git clone https://github.com/Laithwm/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition
jupyter notebook notebooks/handwritten_digit_recognition.ipynb
```

---

## 📊 Results
- Dense Neural Network → ~99.2% accuracy  
- CNN Model → **99.33% test accuracy**  
- Most errors occurred between visually similar digits (e.g., 4 vs 9).  
- Precision, recall, and F1-scores were all above 0.99.

---

## 🧠 Skills
- Data preprocessing & normalization  
- Neural network & CNN modeling  
- Model evaluation & visualization  

---

**Author:** Laith Waqas

Convolutional architectures are crucial for image-based classification tasks, as evidenced by the CNN model's overall superior ability to capture local image features.

📍 Dublin, Ireland   
💼 [LinkedIn](https://www.linkedin.com/in/laithwm)
