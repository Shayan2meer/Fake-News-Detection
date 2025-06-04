# 📰 Fake News Detection with BERT

This project detects fake news using Natural Language Processing (NLP) and a fine-tuned BERT model. It classifies news articles as **real** or **fake** based on their text content.

---

## 📌 Features

- Dataset: Merged real (`True.csv`) and fake (`Fake.csv`) news
- Preprocessing: Lowercasing, punctuation & stopword removal
- Tokenization using `bert-base-uncased`
- PyTorch Dataset and DataLoader implementation
- Fine-tuning BERT for binary classification
- Model evaluation using accuracy, precision, recall, and F1-score
- Trained model saved for future use

---

## 🧪 Workflow

1. Load & label datasets
2. Preprocess text
3. Tokenize using BERT tokenizer
4. Train-validation split
5. Fine-tune BERT model
6. Evaluate & save the model

---

## 🔧 Installation

```bash
pip install transformers torch pandas nltk scikit-learn matplotlib
```

Also download NLTK stopwords:

```python
import nltk
nltk.download('stopwords')
```

---

## 🛠️ Output

- `fine_tuned_bert/`: Saved model and tokenizer
- `combined_csv.csv`: Combined dataset

---

## 🚨 Note

There's a small card price checker (`start()` function) in the notebook which is **not part of fake news detection** — it can be removed if unnecessary.

---

## 📬 Author

Project developed using Google Colab and Hugging Face Transformers.
