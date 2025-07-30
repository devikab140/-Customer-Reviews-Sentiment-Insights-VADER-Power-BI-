# Customer-Reviews-Sentiment-Insights-VADER-Power-BI


Analyze customer reviews to extract actionable sentiment insights, enrich data, and visualize trends in Power BI.

---

## 🎯 **Project Overview**
- Uses **VADER** (Valence Aware Dictionary and sEntiment Reasoner) in Python to detect sentiment:
  - Returns a `compound` score (-1 to +1) and labels reviews as *positive*, *neutral*, or *negative*.
- Keeps text raw (with emojis, punctuation, and caps) to get more accurate sentiment.
- Exports enriched dataset to CSV.
- Builds an interactive **Power BI dashboard** showing:
  - Overall sentiment distribution
  - Sentiment trends over time
  - Sentiment by product or category
  - Top positive and negative reviews

---

## ⚙ **Tech Stack & Tools**
- Python: `pandas`, `nltk` (VADER), `matplotlib`, `seaborn`
- Power BI: interactive visualization
- Dataset: customer reviews (e.g., from Kaggle)

---

## 📊 **Why VADER?**
✅ Fast & lightweight  
✅ Works directly on raw text (handles slang, emojis, punctuation)  
✅ No need for labeled data or training  
✅ Great for dashboards and business reporting

---

## ✂ **Why minimal text cleaning?**
- VADER relies on text features like ALL CAPS and ! for intensity.
- Heavy cleaning (lowercasing, removing punctuation, lemmatizing) would hurt accuracy.
- So we keep text mostly raw except removing missing entries.

---

## 🚀 **How to run**
1. Clone the repo and install requirements:
   ```bash
   pip install pandas nltk matplotlib seaborn

