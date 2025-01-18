# Malicious URL Detection Using Machine Learning

## 📜 Project Overview
This project focuses on detecting malicious URLs using machine learning techniques. With the increasing threat of phishing, malware, and spam attacks, this system provides an automated, accurate, and scalable solution for URL classification. The project leverages feature extraction and ensemble learning techniques to identify malicious URLs in real-time.

---

## 🚀 Features
- **Real-Time URL Detection**: Classifies URLs into categories such as benign, phishing, malware, and defacement.
- **Scalable Architecture**: Easily adaptable to diverse datasets and new threat patterns.
- **Intuitive Interface**: A user-friendly web app for testing URLs.
- **Robust Evaluation**: Ensures high precision, recall, and F1-score across multiple datasets.

---

## 🛠️ Technology Stack
- **Programming Language**: Python
- **Libraries**:
  - Data Handling: Pandas, NumPy
  - Feature Engineering & Model Training: Scikit-learn
  - Visualization: Matplotlib, Seaborn
- **Machine Learning Models**:
  - Decision Tree
  - Random Forest
  - Extra Trees
- **Deployment Framework**: Streamlit
- **Tools**: Jupyter Notebook, Git

---

## 📂 Project Structure
```plaintext
├── data/                  # Datasets used for training and testing
├── codes/                 # Machine learning and Streamlit web app code 
├── README.md              # Project documentation
```

## 📊 Implementation Steps

### Data Preprocessing
- Cleaned and filtered datasets to ensure consistency.
- Converted categorical labels to numerical values.

### Feature Extraction
- Engineered 18 critical features, including URL length, domain properties, and special character counts.

### Model Training and Testing
- Trained Decision Tree, Random Forest, and Extra Trees classifiers.
- Evaluated models on metrics such as Precision, Recall, F1-Score, and Accuracy.

### Deployment
- Built a Streamlit-based web app for user interaction and real-time URL detection.

---

## 📈 Results
- Achieved **95% accuracy** with Random Forest and Extra Trees classifiers.
- High precision and recall for phishing, malware, and defacement categories.
- Demonstrated robustness across multiclass and binary datasets.

---

## 💡 Future Scope
- Integrate advanced techniques like deep learning and NLP for improved detection.
- Build API-based solutions for industry-level applications.
- Expand deployment to mobile and browser-based extensions.
- Incorporate dynamic datasets for continuous learning.

---



## 🙌 Acknowledgments
Special thanks to **Dr. Sharada Ohatkar** and **Harshala Khedlekar** for their valuable guidance and continuous support throughout the project.
