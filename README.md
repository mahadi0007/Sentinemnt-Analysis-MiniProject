# Sentiment Analysis Mini Project

> 📎 **If the preview is not available on GitHub**, you can use this link to view the notebook:  
> [View on NBViewer](https://nbviewer.org/github/mahadi0007/Sentinemnt-Analysis-MiniProject/blob/main/SentimentAnalysis%28mini_project%29.ipynb)

This mini project implements a basic **Sentiment Analysis** system using machine learning techniques in Python. The system analyzes input text (e.g., reviews or tweets) and classifies it into sentiment categories such as **positive**, **negative**, or **neutral**.

## 📁 Project Structure

```
Sentinemnt-Analysis-MiniProject/
├── SentimentAnalysis(mini_project).ipynb   # Jupyter Notebook with full implementation
├── sample.csv                              # Sample dataset used for training/testing
├── sentiment_model.pkl                     # Saved ML model for reuse
└── README.md                               # Project documentation
```

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mahadi0007/Sentinemnt-Analysis-MiniProject.git
   cd Sentinemnt-Analysis-MiniProject
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies: 
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn nltk
  ```

## 📊 Dataset

The project uses a sample CSV file (`sample.csv`) containing text data and corresponding sentiment labels. You can replace this with any text dataset formatted similarly.

## 🚀 How to Use

1. Open `SentimentAnalysis(mini_project).ipynb` in Jupyter Notebook or Colab.
2. Run all cells to:
   - Preprocess the data
   - Train and evaluate the model
   - Make predictions
3. Modify the last section to input custom text for live predictions.

## 🧠 Model

The model is trained and saved as `sentiment_model.pkl` for reuse. You can easily load and use it to predict new text sentiments.

## 📈 Results

- Accuracy: ~X% (update based on your results)


## 🧑‍💻 Author

**Md Mahadi Hasan**  
Master’s Student in Artificial Intelligence at the University of Jyväskylä  
[GitHub Profile](https://github.com/mahadi0007)

