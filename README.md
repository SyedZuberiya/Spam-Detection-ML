📩 Spam Detection using Machine Learning

📌 Project Overview
This project implements a Spam Detection System using Machine Learning (Multinomial Naïve Bayes).
The model classifies messages as Spam or Not Spam based on text analysis.

🚀 Features
Text Preprocessing: Removes special characters and stopwords.

Machine Learning Model: Uses Multinomial Naïve Bayes for classification.

Performance Metrics: Accuracy, confusion matrix, and feature importance visualization.

Plots:

Confusion Matrix for performance evaluation.

Word Importance visualization for top spam words.

📂 Project Structure

📦 Spam-Detection-ML  
│── 📂 data/              # Dataset files  
│── 📂 src/               # Source code  
│── 📜 spam_detector.py   # Main script  
│── 📜 requirements.txt   # Dependencies  
│── 📜 README.md          # Project documentation  


⚙️ Installation & Setup
1️⃣ Clone the repository:
git clone https://github.com/your-username/Spam-Detection-ML.git
cd Spam-Detection-ML

2️⃣ Create a virtual environment (optional but recommended):
python -m venv venv  
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3️⃣ Install dependencies:
pip install -r requirements.txt 

4️⃣ Run the script:
python spam_detector.py  


📊 Dataset Information
Dataset Used: spam.csv

Columns:

label → Spam (1) or Not Spam (0)

message → The text message content

🔍 Model Training & Evaluation
Algorithm Used: Multinomial Naïve Bayes

Train-Test Split: 70% training, 30% testing

Performance Metrics:
✅ Accuracy
✅ Confusion Matrix
✅ Precision, Recall, F1-score

📊 Results & Visualizations

✅ Confusion Matrix
A confusion matrix is generated to evaluate model performance:
![image](https://github.com/user-attachments/assets/0360d2ad-50c8-406c-9ddf-8c708d2ea46d)
✅ Classification Report
A classification report showing precision, recall, F1 Score, Heatmap:
![image](https://github.com/user-attachments/assets/ea96b680-132a-4e16-bef7-a3d0d19c2e80)
✅ ROC Curve
Receiver Operating Characteristic (ROC) curve to analyze model performance:
![image](https://github.com/user-attachments/assets/a9edb33c-9bc4-4f2e-b089-2953dc247136)
✅ Precision-Recall Curve
Precision-Recall curve to evaluate performance on imbalanced data:
![image](https://github.com/user-attachments/assets/e0516927-0abe-423e-bb4f-30d2e94c7241)
✅ Distribution of Spam Prediction Probabilities
Histogram showing the probability distribution of messages classified as spam:
![image](https://github.com/user-attachments/assets/46d0245f-a8b3-4419-a05a-879c8d40ea8f)
✅ Top 10 Words Indicating Spam
Bar chart of the top 10 words most associated with spam messages:
![image](https://github.com/user-attachments/assets/d49a2af7-c037-4a51-904b-f678407c0550)

