
# 🕵️‍♂️ Fake Profile Detector

A hybrid machine learning-based project to detect fake social media profiles by analyzing both **textual** (e.g., bio, username) and **visual** (e.g., profile image) features. This system aims to assist in identifying spam, bot, or fraudulent accounts on social media platforms.

---

## 📌 Project Objective

With the rise of fake accounts on platforms like Instagram, Twitter, and Facebook, this project focuses on building an intelligent classifier that can distinguish between **real** and **fake** profiles using advanced NLP and ML techniques.

---

## 🔍 Features

- ✅ Data preprocessing for structured and unstructured features (bio, image, followers, etc.)
- ✅ Bio analysis using **BERT embeddings**
- ✅ Image analysis using **CART / CNN-based feature extractors**
- ✅ Final classification using **XGBoost**
- ✅ Model evaluation using accuracy, precision, recall, and F1-score
- ✅ Confusion matrix and visualizations for insight

---

## 🧠 Technologies & Tools

| Area         | Tools Used                            |
|--------------|----------------------------------------|
| Language     | Python                                 |
| ML Models    | XGBoost, CART, BERT (Transformers)     |
| Libraries    | Pandas, NumPy, scikit-learn, TensorFlow, Keras |
| NLP          | Hugging Face Transformers, NLTK        |
| Visualization| Matplotlib, Seaborn                    |

---

## 📂 Dataset

The dataset includes labeled profiles with features like:

- `username`, `full_name`, `bio`
- `profile picture` (optional)
- `followers`, `following`, `post count`
- `is_fake` (binary label)

*Note: Due to privacy, a dummy version or link to a similar open-source dataset may be provided.*

---

## 🏗️ Project Structure

```
fake-profile-detector/
├── data/
│   └── social_profiles.csv
├── models/
│   └── xgboost_model.pkl
├── notebooks/
│   └── EDA_and_Training.ipynb
├── utils/
│   ├── preprocess.py
│   └── feature_engineering.py
├── app.py  # Optional frontend using Streamlit or Flask
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/fake-profile-detector.git
cd fake-profile-detector
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run training notebook or script
```bash
python train_model.py
```

### 4. Optional: Launch web app (if Streamlit used)
```bash
streamlit run app.py
```

---

## 📈 Results

| Metric        | Score |
|---------------|-------|
| Accuracy      | 93%   |
| Precision     | 91%   |
| Recall        | 92%   |
| F1-score      | 91.5% |

*Results may vary based on the dataset.*

---

## 🧪 Future Improvements

- Integrate real-time data collection via APIs (Twitter/Instagram)
- Improve image analysis using Vision Transformers or ResNet
- Build a full frontend dashboard for user interaction
- Add language support for bios in multiple languages

---

## 📜 License

MIT License. See `LICENSE` file for more info.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this project and submit a pull request.

---

## 👤 Author

**Suhas M S**  
