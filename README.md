# 📊 Sentiment Analysis on Amazon Product Reviews

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Key Findings & Insights](#key-findings--insights)
- [Recommendations](#recommendations)
- [Files Included](#files-included)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## 📌 Project Overview
This project performs sentiment analysis on the **Amazon Fine Food Reviews** dataset. Using Natural Language Processing (NLP) techniques, we classify customer reviews into **Positive**, **Negative**, or **Neutral** sentiments and extract actionable business insights.

---

## 🎯 Objective
- Analyze customer feedback using textual data.
- Classify sentiments based on polarity scores.
- Visualize sentiment distribution.
- Generate insights to improve product quality.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **TextBlob**

---

## 📂 Dataset
- **Source:** Amazon Fine Food Reviews.
- **Rows used:** First 5,000 entries.
- **Key columns:**
  - `Text` – Review content.
  - `Score` – Rating (1‑5).

---

## ⚙️ Workflow
1. **Data Loading & Exploration**
   - Load CSV with Pandas.
   - Inspect shape and columns.
2. **Data Cleaning**
   - Remove nulls and duplicate reviews.
   - Keep only `Text` and `Score` columns.
3. **Sentiment Analysis**
   - Compute polarity with **TextBlob**.
   - Map polarity to sentiment:
     - `> 0` → **Positive**
     - `< 0` → **Negative**
     - `= 0` → **Neutral**
4. **Visualization**
   - Bar chart of sentiment counts.
   - Pie chart of sentiment percentages.
   - Box plot of rating vs. polarity.

---

## 📈 Key Findings & Insights
- **Majority** of reviews are positive.
- **Negative** feedback frequently mentions:
  - Taste issues
  - Packaging problems
  - Price concerns
- Some **high‑rated** reviews still show neutral sentiment, often due to very short or factual text.
- **Insight:** Ratings and sentiment are correlated but not identical; text analysis adds depth.

---

## 🚀 Recommendations
- Improve **product quality consistency**.
- Strengthen **packaging standards**.
- Enhance **value‑for‑money** perception.

---

## 📎 Files Included
- `sentiment_analysis.ipynb` – Main notebook.
- `summary.docx` – Project summary (generated from this README).
- `README.md` – Project documentation (primary file).
- `PROJECT_README.md` – Duplicate project documentation (this file).

---

## ▶️ How to Run
```bash
# Clone the repository
git clone https://github.com/rohanjangra07/sentiment_analysis.git

# Navigate into the project folder
cd sentiment_analysis

# Install required packages
pip install pandas numpy matplotlib seaborn textblob

# Launch the notebook
jupyter notebook sentiment_analysis.ipynb
```

---

## 📌 Future Improvements
- Integrate **advanced NLP models** (e.g., BERT) for richer sentiment detection.
- Perform **aspect‑based** sentiment analysis.
- Deploy the pipeline as an interactive **web app**.

---

## 👨‍💻 Author
**Rohan Jangra** – B.Tech CSE (AI/ML)

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Key Findings & Insights](#key-findings--insights)
- [Recommendations](#recommendations)
- [Files Included](#files-included)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## 📌 Project Overview
This project performs sentiment analysis on the **Amazon Fine Food Reviews** dataset. Using Natural Language Processing (NLP) techniques, we classify customer reviews into **Positive**, **Negative**, or **Neutral** sentiments and extract actionable business insights.

---

## 🎯 Objective
- Analyze customer feedback using textual data.
- Classify sentiments based on polarity scores.
- Visualize sentiment distribution.
- Generate insights to improve product quality.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **TextBlob**

---

## 📂 Dataset
- **Source:** Amazon Fine Food Reviews.
- **Rows used:** First 5,000 entries.
- **Key columns:**
  - `Text` – Review content.
  - `Score` – Rating (1‑5).

---

## ⚙️ Workflow
1. **Data Loading & Exploration**
   - Load CSV with Pandas.
   - Inspect shape and columns.
2. **Data Cleaning**
   - Remove nulls and duplicate reviews.
   - Keep only `Text` and `Score` columns.
3. **Sentiment Analysis**
   - Compute polarity with **TextBlob**.
   - Map polarity to sentiment:
     - `> 0` → **Positive**
     - `< 0` → **Negative**
     - `= 0` → **Neutral**
4. **Visualization**
   - Bar chart of sentiment counts.
   - Pie chart of sentiment percentages.
   - Box plot of rating vs. polarity.

---

## 📈 Key Findings & Insights
- **Majority** of reviews are positive.
- **Negative** feedback frequently mentions:
  - Taste issues
  - Packaging problems
  - Price concerns
- Some **high‑rated** reviews still show neutral sentiment, often due to very short or factual text.
- **Insight:** Ratings and sentiment are correlated but not identical; text analysis adds depth.

---

## 🚀 Recommendations
- Improve **product quality consistency**.
- Strengthen **packaging standards**.
- Enhance **value‑for‑money** perception.

---

## 📎 Files Included
- `sentiment_analysis.ipynb` – Main notebook.
- `summary.docx` – Project summary (generated from this README).
- `README.md` – Project documentation (primary file).
- `PROJECT_README.md` – Duplicate project documentation (this file).

---

## ▶️ How to Run
```bash
# Clone the repository
git clone https://github.com/rohanjangra07/sentiment_analysis.git

# Navigate into the project folder
cd sentiment_analysis

# Install required packages
pip install pandas numpy matplotlib seaborn textblob

# Launch the notebook
jupyter notebook sentiment_analysis.ipynb
```

---

## 📌 Future Improvements
- Integrate **advanced NLP models** (e.g., BERT) for richer sentiment detection.
- Perform **aspect‑based** sentiment analysis.
- Deploy the pipeline as an interactive **web app**.

---

## 👨‍💻 Author
**Rohan Jangra** – B.Tech CSE (AI/ML)
