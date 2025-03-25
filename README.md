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

✅ Word Importance Plot
Visualization of the most important words in spam classification:

