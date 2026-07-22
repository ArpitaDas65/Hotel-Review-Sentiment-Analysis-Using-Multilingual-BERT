

# 🏨 Hotel Review Sentiment Analysis Using BERT in Assamese Language

An NLP project that classifies **Assamese hotel reviews** into **Positive** or **Negative** and **Neutral** sentiments using **Multilingual BERT (mBERT)**. The project demonstrates how transformer-based models can be applied to sentiment analysis for a low-resource language like Assamese.

---

## 📖 Overview

Sentiment analysis is a Natural Language Processing (NLP) task that identifies the emotional tone expressed in text. In this project, a Multilingual BERT model is fine-tuned to classify Assamese hotel reviews into positive and negative sentiments.

The complete workflow includes:

- Data loading
- Data preprocessing
- Tokenization
- Model training
- Performance evaluation
- Sentiment prediction

This project was developed as part of the **NLP & Generative AI** Internship 

---

## ✨ Features

- Assamese Hotel Review Sentiment Analysis
- Binary Sentiment Classification
- JSON Dataset Support
- Data Cleaning and Preprocessing
- Multilingual BERT Fine-tuning
- PyTorch + Hugging Face Transformers
- Evaluation using Accuracy, Precision, Recall, and F1-Score
- Predict sentiment for new Assamese reviews

---

## 🧠 Model

- **Model:** Multilingual BERT (mBERT)
- **Task:** Binary Text Classification
- **Framework:** Hugging Face Transformers
- **Deep Learning Library:** PyTorch

---

## 📂 Project Structure

```text
Hotel-Review-Sentiment-Analysis/
│
├── dataset/
│   └── hotel_reviews.json
│
├── Assamese_Hotel_Review_Sentiment_Analysis.ipynb
├── requirements.txt
├── README.md
├── LICENSE
└── images/
    └── workflow.png
```

---

## 📊 Dataset

The project uses a **JSON dataset** containing Assamese hotel reviews.

Example:

```json
{
  "review": "হোটেলখন অত্যন্ত পৰিষ্কাৰ আছিল আৰু সেৱা উৎকৃষ্ট আছিল।",
  "label": 1
}
```

Where:

- **review** → Assamese hotel review
- **label**
  - `1` → Positive
  - `0` → Negative

---

## 🔄 Workflow

```text
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Train-Test Split
        │
        ▼
BERT Tokenization
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Sentiment Prediction
```

---

## 🧹 Data Preprocessing

The following preprocessing steps are performed:

- Remove missing values
- Remove duplicate reviews
- Clean unwanted characters
- Normalize Assamese text
- Encode sentiment labels
- Tokenize reviews using the mBERT tokenizer

---

## ⚙️ Training Configuration

| Parameter | Value |
|-----------|-------|
| Model | Multilingual BERT |
| Epochs | 3 |
| Batch Size | 16 |
| Learning Rate | 3e-5 |
| Optimizer | AdamW |
| Loss Function | Cross Entropy Loss |

---

## 📈 Evaluation Metrics

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/ArpitaDas65/Hotel-Review-Sentiment-Analysis.git
```

Move into the project directory:

```bash
cd Hotel-Review-Sentiment-Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Assamese_Hotel_Review_Sentiment_Analysis.ipynb
```

Run all cells to:

- Load the JSON dataset
- Train the BERT model
- Evaluate performance
- Predict sentiments for new reviews

---

## 📌 Future Improvements

- Aspect-Based Sentiment Analysis
- Multi-Class Sentiment Classification
- Web Application using Streamlit
- REST API using Flask or FastAPI
- Compare mBERT with IndicBERT and MuRIL
- Deploy the model on Hugging Face Spaces

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## 👩‍💻 Author

**Arpita Das**

BCA Student | AI & NLP Enthusiast

- GitHub: https://github.com/ArpitaDas65
- LinkedIn: https://www.linkedin.com/in/arpitadas-ai

---

## 📜 License

This project is released under the **MIT License**.

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
