# Fake Book Review Detection 
### Group Project – Using Machine Learning to Improve Goodreads' Credibility  

## Project Overview  
This project analyzes and classifies **fake vs. real book reviews** using Natural Language Processing (NLP) techniques. We explore text preprocessing methods, sentiment analysis, feature extraction, and machine learning models to build an effective classification system.  

### Key Steps:
1. **Data Preprocessing**: Cleaned and prepared the dataset for analysis.  
2. **Sentiment Analysis**: Analyzed the emotional tone of reviews.  
3. **Feature Engineering**: Applied TF-IDF and Bag-of-Words (BoW) techniques for feature extraction.  
4. **Model Training**: Built classification models to detect fake reviews.  
5. **Evaluation & Insights**: Assessed model performance and derived insights.  

---

## Exploratory Data Analysis (EDA)  
Before modeling, we conducted EDA to gain insights into the dataset. We aimed to answer:  
- Do fake reviews have more extreme ratings (very high or low) than real ones?  
- Is the dataset imbalanced?  
- Do fake reviews use more generic or repetitive language?  
- Is there a significant difference in average ratings between fake and real reviews?  
- Do fake reviews have fewer unique words, indicating repetitive patterns?  

---

## Tools & Technologies  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn  
- **Models:** Random Forest, KNN, SVM, Naive Bayes (Multinomial, Bernoulli)   
- **NLP Techniques:** Tokenization, Lemmatization, TF-IDF, Bag-of-Words  

---

## Results & Insights  
- **Best Performing Model:** SVM with 90% accuracy.  
- **Key Features:** TF-IDF/BoW features were significant predictors. Sentiment Score alone wasn't sufficient.  
- **Insights:** 

---

## Future Improvements  
- Enhance feature engineering with deep learning embeddings (e.g., Word2Vec, BERT).  
- Collect more real-world datasets to improve model generalization.  
- Deploy the model with a user-facing API for real-time review classification.  

---

## Contributors  
- Karen Bou Daou 
- Juliana Hubacova
- Hamza Javed
- Axel Peronnet 

---

## License  
This project is for academic purposes under the MIT License.  

---

## How to Run the Notebook  
1. Clone the repository:  
   ```bash
   git clone https://github.com/julianahubacova/detecting_fake_reviews.git


