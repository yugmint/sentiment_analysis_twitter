
# 🦠 COVID-19 Twitter Sentiment Analysis

This project explores public sentiment surrounding the emergence of a new COVID-19 strain using Twitter data. With rising concern over rapid public reactions—such as panic buying or misinformation—the goal is to leverage Natural Language Processing (NLP) techniques to analyze real-time sentiment expressed on social media, helping health authorities make informed decisions.

---

## 📌 Use Case

As part of an initiative for the **Ministry of Health and Family Welfare**, this analysis aims to determine **how people are reacting to a newly detected COVID-19 strain**. Traditional survey methods are often too slow in fast-changing scenarios like a pandemic. Instead, this project taps into Twitter data to quickly assess public mood and sentiment.

---

## 📊 Dataset

- **Source**: Kaggle  
- **Size**: 3,798 tweets and 6 features  
- **Nature**: Each tweet is labeled with sentiment (Positive, Negative)

---

## 🧹 Preprocessing

Textual data was cleaned and normalized using the following NLP techniques:

- Stopword removal  
- Lemmatization  
- Frequency Dictionary-based token analysis

---

## 🤖 Model

- **Algorithm**: Logistic Regression  
- **Evaluation Metric**: Accuracy on test set  
- **Test Accuracy**: `57.89%`

---

## 📁 Project Structure

```

📦 covid-twitter-sentiment
│
├── covid\_twitter\_sentiment\_analysis.ipynb  # Main analysis notebook
└── README.md                               # Project overview and documentation

````

---

## 💬 Sentiment Labels

- **Positive**  
- **Negative**

(*Neutral tweets were not labeled in this dataset*)

---

## 🚀 Deployment

This project currently runs as a standalone Jupyter Notebook and has **not been deployed** using any web framework.

---

## 📌 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yugmint/sentiment_analysis_twitter.git
````

2. Open the notebook:

```bash
jupyter notebook covid_twitter_sentiment_analysis.ipynb
```

---



---

## 📬 Contact

**Yugendra Salunke**
Data Scientist
📧 [yugendra0511@gmail.com](mailto:yugendra0511@gmail.com)
📞 +91-8109079427
[LinkedIn](https://www.linkedin.com/in/yugendra-salunke/) | [GitHub Portfolio](https://github.com/yugmint)

---

## ⭐️ Acknowledgment

Thanks to **Kaggle** for the COVID-19 tweet dataset.

---

## 🔮 Future Enhancements

* Use more advanced models (e.g., BERT, LSTM)
* Expand to multilingual sentiment analysis
* Deploy using Streamlit or Flask for real-time, interactive analysis

```


```
