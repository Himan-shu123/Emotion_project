# Emotion_project 

# 🧠 Emotion Detection with Logistic Regression

This project demonstrates a basic **Emotion Detection System** using machine learning (Logistic Regression) and **TF-IDF vectorization**. It includes a simple dataset, text preprocessing, model training, evaluation, and a user-friendly interactive interface with `ipywidgets`.

---

## 📂 Project Structure

- **Data**: A small sample of labeled emotional text.
- **Preprocessing**: Stopword and special character removal using `neattext`.
- **Model**: Trained using `LogisticRegression` and `TfidfVectorizer`.
- **Evaluation**: Accuracy, classification report, and confusion matrix visualization.
- **UI**: Built with `ipywidgets` for real-time predictions in a Jupyter Notebook.
- **Model Saving**: Model is saved using `joblib`.

---

## 🚀 How to Run

1. **Install Dependencies**

```bash
pip install pandas numpy seaborn matplotlib scikit-learn neattext joblib ipywidgets
```

2. **Launch Jupyter Notebook**

```bash
jupyter notebook
```

3. **Run the Notebook**

Go through each cell step-by-step. After training the model, you can interact with the UI at the end to predict the emotion of your custom input.

---

## 📊 Sample Dataset

```plaintext
Text:                          Emotion:
---------------------------   ----------
"I am so happy today!"        happy  
"This is terrible"            angry  
"I feel sad and down"         sad    
...
```

Supports emotions like:
- `happy`
- `sad`
- `angry`
- `fear`
- `neutral`

---

## 📌 Key Features

- ✅ Simple and readable implementation
- ✅ TF-IDF + Logistic Regression pipeline
- ✅ Inline model evaluation (accuracy & confusion matrix)
- ✅ Interactive text input with real-time predictions using `ipywidgets`
- ✅ Model persistence using `joblib`

---

## 📷 Screenshots

> You can add screenshots here of:
> - Confusion matrix plot  
> - UI widget showing a predicted emotion

---

## 💡 Example Usage

```python
Your Text: "I am feeling very happy today!"
🧠 Predicted Emotion: `happy`
```

---

## 🧰 Tech Stack

- Python
- Jupyter Notebook
- Scikit-learn
- Neattext
- Matplotlib / Seaborn
- ipywidgets

---

## 📁 Model Output

Saved model file:  
```bash
emotion_classifier.pkl
```

---

## ✅ To Do (Optional Enhancements)

- [ ] Expand dataset (Kaggle-based large dataset)
- [ ] Add more emotions like surprise, disgust, etc.
- [ ] Use advanced models (SVM, Random Forest, or Deep Learning)
- [ ] Export to Streamlit or Flask web app

---

## 📜 License

This project is open-source and available for personal or educational use.
