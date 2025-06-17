# 😃 Emotion Detection with Rule-based NLP (Vietnamese)

This project focuses on detecting emotional sentiment in Vietnamese text using a rule-based approach. It involves building a custom emotion lexicon and applying logical rules to classify input sentences into emotion categories such as positive or negative.

---

## 📄 Dataset

- **Source**: Manually created dataset of Vietnamese sentences  
- **Format**: `.txt` and `.csv` files for sample text and emotion word dictionary  
- **Categories**: Positive (1), Negative (-1)

---

## 🧠 Techniques Used

- Vietnamese text preprocessing: lowercasing, punctuation removal, tokenization  
- Dictionary-based sentiment scoring using positive/negative word lists  
- Rule-based classification logic (count-based comparison)  
- Accuracy evaluation by comparing predicted vs. labeled sentiments  
- Batch sentiment prediction from tokenized CSV files

---

## 🎯 Goal

- Build a transparent, interpretable rule-based emotion detection system for Vietnamese  
- Perform basic sentiment classification without using machine learning  
- Provide a lightweight prototype for future improvement or extension

---

## ✅ Results

- The predicted labels (`pre_Sentiment`) matched ground-truth labels (`Sentiment`) on **~84.7%** of test samples  
- Results are saved to CSV for easy inspection, validation, or dashboard integration

---

## 🛠️ Tools & Libraries

- Python, Pandas, re (Regex)  
- Text preprocessing techniques: lowercasing, punctuation removal, tokenization  

---

⭐ This project was developed during my learning journey and reflects my ability to apply concepts into practice. It continues to be improved as I grow
