📊 Sentiment Analysis on Amazon Product Reviews
📌 Project Overview

This project performs sentiment analysis on the Amazon Fine Food Reviews dataset. It uses Natural Language Processing (NLP) techniques to classify customer reviews into Positive, Negative, or Neutral sentiments and extract useful business insights.

🎯 Objective 
Analyze customer feedback using text data
Classify sentiments based on polarity scores
Visualize sentiment distribution
Generate insights for improving product quality
🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
TextBlob
📂 Dataset
Dataset used: Amazon Fine Food Reviews
First 5000 rows were used for analysis 
Key columns:
Text → Review content
Score → Rating
⚙️ Workflow
1. Data Loading & Exploration
Loaded dataset using Pandas
Checked structure, shape, and columns
2. Data Cleaning
Removed null values
Removed duplicate reviews
Selected relevant columns
3. Sentiment Analysis
Used TextBlob to calculate polarity
Classified:
Positive (> 0)
Negative (< 0)
Neutral (= 0)
4. Data Visualization
Bar Chart → Sentiment distribution
Pie Chart → Percentage share
Box Plot → Rating vs polarity
📈 Key Findings
Majority of reviews are positive
Negative reviews highlight:
Taste issues
Packaging problems
Price concerns
Some high-rated reviews show neutral sentiment
💡 Insights
Ratings and sentiment are related but not identical
Text analysis provides deeper understanding than ratings
Short reviews often result in neutral sentiment
🚀 Recommendation

Focus on improving:

Product quality consistency
Packaging standards
Value for money
📎 Files Included
Sentiment_Analysis.ipynb → Main notebook
summary.docx → Project summary
README.md → Project documentation
▶️ How to Run
Clone the repository
git clone https://github.com/your-username/repo-name.git
Install dependencies
pip install pandas numpy matplotlib seaborn textblob
Run the notebook
jupyter notebook
📌 Future Improvements
Use advanced NLP models (like BERT)
Perform aspect-based sentiment analysis
Deploy as a web app
👨‍💻 Author

Rohan Jangra
B.Tech CSE (AI/ML)
