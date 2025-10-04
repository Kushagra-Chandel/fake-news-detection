# 📰 Fake News Detection using Machine Learning

This project aims to classify news articles as **Fake** or **Real** using a supervised machine learning approach. Built using Python, pandas, and scikit-learn, it leverages logistic regression for binary classification and includes full preprocessing, model training, and deployment steps.

---

## 📂 Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) and consists of two files:

- `Fake.csv`: Contains fake news articles
- `True.csv`: Contains real news articles

Each file includes:
- `title`: Headline of the article  
- `text`: Full article content  
- `subject`: Category of news  
- `date`: Publication date  

---

## ⚙️ Project Structure

| File | Description |
|------|-------------|
| `Fake_News_Prediction.ipynb` | Main Jupyter notebook with preprocessing, model training, and prediction |
| `Fake News Prediction.joblib` | Saved logistic regression model |
| `Fake.csv`, `True.csv` | Raw datasets |
| `README.md` | Project overview |
| `requirements.txt` | Python dependencies (optional)

---

## 🧠 Model Details

- **Algorithm**: Logistic Regression  
- **Vectorization**: TF-IDF  
- **Accuracy**: ~90% on test data  
- **Libraries Used**:
  - `pandas`
  - `scikit-learn`
  - `joblib`

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Kushagra-Chandel/fake-news-detection.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open `Fake_News_Prediction.ipynb` in Jupyter or Google Colab
   - Upload `Fake.csv` and `True.csv` when prompted
   - Run all cells to train or load the model

---

## 🔍 Sample Prediction

```python
x = x_test[8]
prediction = model.predict([x])

if prediction[0] == 0:
    print("🟢 The news is Real")
else:
    print("🔴 The news is Fake")
```

---

## 📌 Future Improvements

- Add deep learning models (LSTM, BERT)
- Deploy using Flask or Streamlit
- Integrate real-time news scraping

---

## 🙋‍♂️ Author

**Kushagra Chandel**  
Final-year B.Tech (AI & ML)  
Passionate about GenAI, product thinking, and solving real-world problems with machine learning.

---

## 📬 Contact

- [LinkedIn](https://www.linkedin.com/in/kushagra-chandel)
- [GitHub](https://github.com/Kushagra-Chandel)
- [Email](chandelkushagra@gmail.com)
```

---

Tu chahe toh isme apna email, portfolio link, ya placement-specific note bhi daal sakta hai.  
Bata, chahega main ek Streamlit UI bhi design karwa doon iske liye? Tera repo ab spotlight mein hai 💡
