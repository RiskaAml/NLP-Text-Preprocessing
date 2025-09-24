# NLP-Text-Preprocessing
# 📄 SMS Spam Detection — Text Preprocessing

## **Description**  
This project demonstrates **text preprocessing** on the SMS Spam Collection dataset for classifying messages into **spam** and **ham (non-spam)**.  

The workflow covers essential NLP steps: text cleaning, tokenization, stopword removal, stemming/lemmatization, and word frequency visualization.  

---

## **Dataset**  
- Source: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- Main columns:  
  - `v1` → label (`spam` or `ham`)  
  - `v2` → SMS message content  

---

## **Workflow**  

1. **Data Import & Exploration**  
   - Load CSV and preview the first 5–10 rows.  
   - Check the distribution of spam vs ham.  
   - Handle missing values if present.  

2. **Text Cleaning**  
   - Convert text to lowercase.  
   - Remove numbers, symbols, and punctuation.  
   - Remove URLs, mentions, and extra whitespaces.  

3. **Tokenization**  
   - Split messages into tokens.  

4. **Stopword Removal**  
   - Remove common non-informative words (e.g., “the”, “is”, “to”).  

5. **Stemming / Lemmatization**  
   - Normalize words to their base form.  
   - Example: `messages` → `message`.  

6. **Analysis & Visualization**  
   - Identify most frequent words in spam vs ham.  
   - Visualize with WordCloud or bar charts.  

7. **Optional**  
   - Compare average message length between spam and ham.  
   - Save the preprocessed dataset into a new CSV (`sms_preprocessed.csv`).  

---

## **Expected Outputs**  
- **Visualizations**: WordClouds or bar charts.  
- **Screenshots**: Before vs after preprocessing samples.  
- **Insights**:  
  - Example: “Common spam words include *free, win, urgent*.”  
  - Example: “Common ham words include *call, ok, love*.”  
