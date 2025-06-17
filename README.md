# 📚 Arabic Book Classification using NLP

This project aims to enhance book discovery within the Arabic literature domain by building a classification system that automatically assigns genres to Arabic books based on their metadata and textual information.

> Developed as part of the course **CCAI-413: Natural Language Processing**, under the supervision of Dr. Alaa Alharthi.

---

## 🧠 Objective

To classify over 8,000 Arabic book titles (from Jamalon, the largest Middle Eastern bookstore) into genres using both classical machine learning and deep learning techniques.

---

## 🛠️ Technologies Used

- **Languages & Tools**: Python, Google Colab
- **ML Algorithms**: SVM, Logistic Regression, Naive Bayes
- **DL Models**: CNN, LSTM
- **Text Processing**: TF-IDF, Tokenizer, LabelEncoder, Padding
- **Libraries**: scikit-learn, Keras, TensorFlow, pandas, NumPy

---

## 📁 Dataset

- 8,000+ Arabic books from [Jamalon](https://jamalon.com/)
- Features: Title, Author, Publisher, Year, Description, and Category
- Target: Book genre classification

---

## 📊 Methodology

### Traditional Machine Learning:
- **TF-IDF Vectorization**
- Models:
  - SVM: Accuracy 75.47%
  - Logistic Regression: Accuracy 75.36%
  - Naive Bayes: Accuracy 73.69%

### Deep Learning:
- **Preprocessing**: Tokenizer + Padding
- **CNN**:
  - Embedding + Conv1D + MaxPooling + Dense
  - Accuracy: 73.61%
- **LSTM**:
  - Embedding + LSTM Layer
  - Accuracy: 74.05%

> 🧪 Deep learning models showed overfitting due to limited dataset size and highly informative titles.

---

## ⚖️ Results & Observations

- Traditional ML models slightly outperformed DL models due to the nature of the data.
- SVM performed best overall, but Naive Bayes had the lowest overfitting.
- Deep models (CNN & LSTM) struggled with generalization, highlighting dataset size as a key limitation.

---

## 🎯 Conclusion

This project demonstrates the effectiveness of traditional ML techniques over deep learning for medium-sized Arabic text datasets. The final system provides a strong foundation for enhancing Arabic book recommendation engines and discovery platforms.

---

## 👥 Team Members

- **Lamis Melebari** 
- **Doaa Brnawi**  
- **Joory Abdulfattah**  

---

## 📬 Supervisor

**Dr. Alaa Alharthi**  
Email: asalharthi@uj.edu.sa
