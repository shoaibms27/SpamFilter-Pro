📧 Email Spam Classifier
An end-to-end machine learning project that classifies emails as spam or ham (not spam). This project includes data preprocessing, feature extraction, model training, evaluation, and deployment using Streamlit.

🚀 Features
Data Preprocessing: Cleans and prepares email text data.

Feature Extraction: Utilizes TF-IDF Vectorization to convert text data into numerical features.

Model Training: Implements machine learning algorithms, including Multinomial Naive Bayes.

Evaluation: Assesses model performance using metrics like accuracy, precision, recall, and F1 score.

Deployment: Provides an interactive web interface using Streamlit for users to input email content and receive classification results.

📂 Project Structure
markdown
Copy
Edit
email-spam-classifier/
├── app.py
├── model.py
├── preprocess.py
├── requirements.txt
├── README.md
└── dataset/
    └── spam.csv
🛠️ Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/your-username/email-spam-classifier.git
Navigate to the Project Directory:

bash
Copy
Edit
cd email-spam-classifier
Install Required Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
📊 Dataset
The model is trained on the SpamAssassin Public Corpus, which contains labeled email messages categorized as spam or ham.

🧠 Model Performance
The classifier achieves the following performance metrics:

Accuracy: 94.87%

Precision: 95.00%

Recall: 94.50%

F1 Score: 94.75%

🖥️ Usage
Run the Streamlit Application:

bash
Copy
Edit
streamlit run app.py
Interact with the Classifier:

Open the provided local URL in your web browser.

Enter the email content into the text box.

Click the "Classify" button to determine if the email is spam or ham.