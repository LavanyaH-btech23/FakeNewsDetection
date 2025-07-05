<h1 align="center">📰 Fake News Detection using Machine Learning</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Colab-Python-yellow?style=for-the-badge&logo=googlecolab&logoColor=white"/>
  <img src="https://img.shields.io/badge/ML-LogisticRegression-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-blue?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

This project aims to detect whether a news headline or article is **real** or **fake** using machine learning techniques. Built using **Google Colab**, this project collects **real-time news** and applies **text classification algorithms** to classify them.

---

## 🧠 Features

✅ Real-time news scraping using NewsAPI / Google News  
✅ Dataset combining real and fake headlines  
✅ Text vectorization using **TF-IDF**  
✅ ML models: Logistic Regression, SVM  
✅ Accuracy up to **94.5%**  
✅ (Optional) Real-time headline prediction

---

## 📁 Project Files

| File                        | Description                                |
|----------------------------|--------------------------------------------|
| `Fake_News_Detector.ipynb` | Main Colab notebook                        |
| `real_news.csv`            | Real news headlines                        |
| `fake_news.csv`            | Fake news samples                          |
| `requirements.txt`         | Python libraries needed                    |
| `output.png` (optional)    | Screenshot of results (accuracy/confusion) |
| `README.md`                | This file                                  |

---

## 📊 Results Snapshot

![Demo Output](output.png)

---

## 🧪 Tech Stack

- **Language:** Python 3  
- **Libraries:** Pandas, NumPy, scikit-learn, NLTK  
- **Notebook:** Google Colab  
- **ML Model:** Logistic Regression, SVM  

---

## 🛠️ Installation Guide (Optional)

```bash
# Clone the repository
git clone https://github.com/LavanyaH-btech23/FakeNewsDetection.git

# Install requirements
pip install -r requirements.txt

# Open notebook in Jupyter or Colab
