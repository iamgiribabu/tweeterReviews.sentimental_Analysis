# 🧠 Sentiment Analysis on Twitter Reviews

A machine learning project to classify sentiment in Twitter reviews into four categories: **Positive**, **Negative**, **Neutral**, and **Irrelevant**. This project includes full preprocessing, visualization, and modeling using a Deep Neural Network with BERT embeddings.

---

## 📊 Sentiment Distribution

- **Negative:** 30.21%  
- **Positive:** 27.90%  
- **Neutral:** 24.47%  
- **Irrelevant:** 17.39%  
> 🔎 The dataset was noticeably imbalanced, requiring resampling.

---

## 🔧 Preprocessing & EDA

- Expanded shortened words (e.g., "can't" → "cannot")
- Removed stopwords, special characters, and noise
- Created word clouds to visualize frequently used words per sentiment
- Explored class distribution through bar charts and visual aids

---

## 🤖 Modeling Approach

- Used **BERT** for generating text embeddings
- Resampled imbalanced data using **SMOTE**
- Built a **Sequential Deep Neural Network**

### 🧪 Final Results:
- **Accuracy:** `0.7827`
- **Loss:** `0.6924`
- **Validation Accuracy:** `0.7530`
- **Validation Loss:** `0.7834`
- **Learning Rate:** `5.0000e-01`

---

## 💡 Lessons Learned

I initially experimented with a more complex **LSTM model**, but it underperformed (~30–40% accuracy on 74K rows).  
✅ Surprisingly, a simpler DNN architecture with proper embeddings and resampling provided significantly better results.

---

## 📁 Project Structure

## 📷 Thumbnail

![Sentiment Analysis Thumbnail](A_2D_digital_graphic_design_infographic_depicts_Se.png)
