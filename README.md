# Spam Email Classifier

A beginner-friendly Machine Learning project that classifies SMS messages as **Spam** or **Ham** (Not Spam) using Python, Scikit-learn, and TF-IDF vectorization. This project includes text preprocessing, model training, evaluation, and vocabulary visualization using WordClouds.

---

## 🚀 Features

- Classifies SMS messages as spam or not spam
- Uses TF-IDF to convert text to numeric features
- Built with Naive Bayes (MultinomialNB) algorithm
- Accuracy score, confusion matrix, and classification report
- WordCloud visualizations for spam and ham messages
- Live predictions on custom sample messages

---

## 🛠️ Tech Stack

| Category           | Tools Used                                  |
| ------------------ | ------------------------------------------- |
| Language           | Python                                      |
| Libraries          | Pandas, Scikit-learn, Matplotlib, WordCloud |
| ML Algorithm       | Naive Bayes (MultinomialNB)                 |
| Feature Extraction | TF-IDF Vectorizer                           |
| IDE                | Jupyter Notebook                            |

---

## 📂 Dataset

- **Name:** SMS Spam Collection Dataset
- **Source:** [Kaggle Datasets](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download)
- **File:** `spam.csv` (included in this repo)

This dataset contains 5,572 SMS messages labeled as either "spam" or "ham".

---

## 📊 WordCloud Visualizations

- Spam message vocabulary (black background):
  ![Spam WordCloud](/WordCloud-Images/Spam-msg.png)

- Ham message vocabulary (white background):
  ![Ham WordCloud](/WordCloud-Images/Ham-msg.png)

---

## 📌 How It Works

1. **Load Dataset** – Reads and cleans the SMS spam dataset.
2. **Preprocess Data** – Labels are converted (ham → 0, spam → 1).
3. **WordClouds** – Generates WordClouds for both spam and ham.
4. **TF-IDF Vectorization** – Converts text into numeric vectors.
5. **Train-Test Split** – 80% training, 20% testing.
6. **Train Model** – Uses Naive Bayes classifier.
7. **Evaluate Model** – Prints accuracy, confusion matrix, and report.
8. **Live Prediction** – Test the model with your own text inputs.

---

## 🔍 Sample Predictions

```python
sample = ["Congratulations! You've won a free iPhone. Click the below link to claim"]
# Output: Spam

sample = ["Hey, are we still meeting at 6 PM?"]
# Output: Not Spam
```

## 📝 License

This project is licensed under the **MIT License**.
Feel free to use, modify, and distribute for personal and commercial purposes.

---

## 🙌 Contribution

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

## 💬 Contact

Created with ❤️ by Sushmitha Shettigar
