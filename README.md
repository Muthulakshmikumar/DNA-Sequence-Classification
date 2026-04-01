🧬 DNA Sequence Classification using Machine Learning

 📌 Project Overview
This project focuses on classifying DNA sequences into biological categories such as:
- Bacteria
- Virus
- Human
- Plant

The model uses Machine Learning techniques to analyze DNA patterns and predict the class of a given sequence.


🎯 Objective
To build a machine learning system that:
- Accepts DNA sequences as input
- Extracts meaningful patterns using K-mer technique
- Converts sequences into numerical features using TF-IDF
- Predicts the biological class accurately


⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- ipywidgets


 🧠 Methodology

 1. Data Preprocessing
- Converted DNA sequences to uppercase
- Removed invalid characters (only A, T, G, C retained)
- Filtered out very short sequences

 2. Feature Engineering (K-mer)
- DNA sequences are broken into smaller patterns called K-mers
- Example:ATGCGT → ATGC, TGCG, GCGT


 3. Vectorization (TF-IDF)
- Converted K-mer patterns into numerical features
- Reduced importance of common patterns and highlighted unique ones


4. Model Training
Multiple classification models were used:
- Logistic Regression
- Naive Bayes
- Decision Tree
- Linear SVM


5. Model Evaluation
The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)


6. Model Selection
The best-performing model was selected based on accuracy and class-wise performance.


📊 Exploratory Data Analysis (EDA)
Performed analysis to understand:
- Class distribution
- Sequence length distribution
- GC-content distribution
- Feature statistics

Visualizations were created using Matplotlib.

🧪Final Prediction System
- User enters a DNA sequence
- The system processes the sequence
- The trained model predicts the biological class

Output example:Predicted Class: Bacteria
