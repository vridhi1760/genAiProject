# 🛍️ Product Feature Extractor

This project extracts product features and their corresponding sentiments (positive, negative, neutral) from customer review texts using a transformer-based model (`flan-t5-large`). It visualizes the results to help businesses understand customer opinions on specific features.

---

## 📌 Features

- Extracts product-related features from natural-language customer reviews
- Performs sentiment analysis (positive, negative, neutral) for each feature
- Visualizes sentiment distribution using pie and bar charts
- Designed to work with simple `.csv` files containing customer reviews

---

## 📁 Project Structure

```
├── Product_Feature_Extractor.ipynb   # Main notebook
├── Reviews.csv                       # Sample or actual review data
├── requirements.txt                  # Python dependencies
├── README.md                         # Project overview and usage
├── .gitignore                        # Files to exclude from Git tracking
```

---

## 🧰 Requirements

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Ensure your CSV file has a column named `review`.
2. Open the notebook `Product_Feature_Extractor.ipynb` in Jupyter or Colab.
3. Follow the notebook steps to:
   - Load and clean the reviews
   - Extract features and sentiments using the transformer model
   - Visualize sentiment analysis results

---

## 📈 Sample Outputs

- Pie charts showing top positive and negative features
- Bar charts for sentiment breakdown per feature



---

## 🧠 Model Info

- Model used: [FLAN-T5 Large](https://huggingface.co/google/flan-t5-large)
- Fine-tuned for instruction-following and reasoning tasks

---

## 🔮 Future Enhancements

- Add more robust aspect-based sentiment classification
- Build a Streamlit dashboard for easy interaction
- Enable batch processing of large review datasets

---
