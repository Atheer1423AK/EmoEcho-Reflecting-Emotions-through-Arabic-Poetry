# 📜 EmoEcho: Reflecting Emotions through Arabic Poetry

## 📌 Project Overview
Arabic poetry carries deep cultural and emotional significance, yet its automated analysis remains a challenging task due to its linguistic complexity and metaphorical expressions. While much of Arabic NLP research has focused on prose and dialects, poetry—especially emotional classification in verse—has been underexplored.

**EmoEcho** addresses this gap by classifying emotions in Arabic poetry using a curated dataset labeled for joy, sadness, and love.  
This work supports:
- Cultural preservation and emotion-aware digital libraries
- Educational tools for literary studies in digital humanities

Two deep learning approaches were evaluated:
1. **AraBERT** — fine-tuned specifically for poetry  
2. **CNN-LSTM hybrid** — designed for sequential language processing  

**Top Results**:
- **AraBERT**: 75.1% Accuracy | 0.7512 F1-score  
- **CNN-LSTM**: Lower performance, highlighting transformer models’ advantage in capturing poetic nuances

---

## 🎯 Objectives
- Implement emotion classification for Arabic poetry
- Apply advanced NLP models tailored for Arabic text (AraBERT)  
- Explore hybrid deep learning approaches combining CNN and LSTM
- Enable practical applications in cultural preservation and digital education

---

## 📂 Dataset
**Source**: [Arabic Poetry Emotions Dataset on Kaggle](https://www.kaggle.com/datasets/sakibshahriar95/arabic-poetry-emotions-dataset)  

A dataset of Arabic poems categorized into three emotions:
- Joy  
- Sadness (including lamentation)  
- Love  

**Preprocessing steps**:
- Normalization  
- Tokenization  
- Diacritic removal  
- Handling class imbalance through up-/down-sampling

---

## 🛠 Methodology
1. **Preprocessing**: Normalize text, tokenize, remove diacritics if needed  
2. **Embeddings**: Use AraBERT tokenizer or Word2Vec (for CNN-LSTM)  
3. **Model Training**:
   - Fine-tune **AraBERT**
   - Train **CNN-LSTM hybrid**
4. **Evaluation**: Accuracy, Precision, Recall, F1-score, and Confusion Matrix  

---

## 📊 Results

| Model           | Accuracy | F1-score |
|-----------------|----------|----------|
| AraBERT         | 75.1%    | 0.7512   |
| CNN-LSTM        | ~59%     | ~0.64    |

AraBERT significantly outperformed CNN-LSTM, demonstrating its effectiveness in handling the nuanced language of Arabic poetry.


