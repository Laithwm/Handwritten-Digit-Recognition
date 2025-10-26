## 📊 Results & Discussion

The project effectively illustrates how deep learning works for handwritten digit recognition.


Even without convolutional layers, the baseline **Dense Neural Network** demonstrated strong generalisation, achieving approximately **99.2% validation accuracy**.  
On unseen data, however, the **Convolutional Neural Network (CNN)** achieved **99.33% test accuracy**, further enhancing stability and spatial feature extraction.

The majority of the digits were correctly classified, according to the **confusion matrix**, with only a small amount of confusion between visually similar digits (for example, 4 vs. 9 or 5 vs. 8).  
F1-scores, precision, and recall were all above **0.99**, suggesting steady and balanced model performance.

Convolutional architectures are crucial for image-based classification tasks, as evidenced by the CNN model's overall superior ability to capture local image features.

