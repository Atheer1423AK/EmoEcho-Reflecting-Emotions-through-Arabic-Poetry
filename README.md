# 🎭 EmoEcho: Reflecting Emotions through Arabic Poetry

## 📜 Project Overview
Arabic poetry carries deep cultural and emotional significance, yet its automated analysis remains a challenging task due to its linguistic complexity and metaphorical expressions. While much of Arabic NLP has focused on prose and dialects, poetry—especially emotional classification in verse—has been underexplored.

**EmoEcho** tackles this gap by classifying emotions in Arabic poetry using a curated dataset labeled for **😊 joy**, **😢 sadness**, and **❤️ love**.  
This work supports:
- 🏛 Cultural preservation and emotion-aware digital libraries
- 🎓 Educational tools for literary studies in digital humanities

Two deep learning approaches were evaluated:
1. 🤖 **AraBERT** — fine-tuned specifically for poetry  
2. 🌀 **CNN-LSTM hybrid** — designed for sequential language processing  

**Top Results**:
- **AraBERT**: 🥇 **75.1% Accuracy** | **0.7512 F1-score**  
- **CNN-LSTM**: 📉 Lower performance, highlighting transformer models’ advantage in capturing poetic nuances

---

## 🎯 Objectives
- Bring **emotion classification** to Arabic poetry
- Use advanced **NLP models tailored for Arabic text** (AraBERT)  
- Explore hybrid approaches combining **CNN with LSTM**
- Enable practical cultural applications — from digital archives to teaching tools

---

## 📂 Dataset
📌 **Source**: [Arabic Poetry Emotions Dataset on Kaggle](https://www.kaggle.com/datasets/sakibshahriar95/arabic-poetry-emotions-dataset)  

A dataset of Arabic poems categorized into three emotions:
- 😊 Joy  
- 😢 Sadness (including lamentation)  
- ❤️ Love  

**Preprocessing steps**:
- 🔤 Normalization  
- ✂️ Tokenization  
- 📝 Diacritic removal  
- ⚖ Handling class imbalance through up-/down-sampling

---

## 🛠 Methodology
1. 🧹 **Preprocess Text** – Normalize, tokenize, remove diacritics if needed  
2. 📚 **Build Embeddings** – Use AraBERT tokenizer or Word2Vec (for CNN-LSTM)  
3. 🏋️ **Train Models**:
   - Fine-tune **AraBERT**
   - Train **CNN-LSTM hybrid**
4. 📊 **Evaluate** – Accuracy, Precision, Recall, F1-score, and Confusion Matrix  

---

## 📈 Results

| 🧠 Model         | 🎯 Accuracy | 📊 F1-score |
|------------------|------------:|------------:|
| 🤖 AraBERT       | 75.1%       | 0.7512      |
| 🌀 CNN-LSTM      | ~59%        | ~0.64       |

✅ AraBERT significantly outperformed CNN-LSTM, underscoring its strength in handling the nuanced language of Arabic poetry.

