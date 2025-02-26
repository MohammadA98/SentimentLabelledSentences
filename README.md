# **Final Project: Comparing Lexicon-Based and Machine Learning Approaches for Sentiment Analysis (VADER vs. Logistic Regression)**  
### **Project Status: [Active]**  

## **Introduction**  
This project aims to analyze sentiment in **Amazon, IMDB, and Yelp reviews** using **two different approaches**:  
1. **Lexicon-Based Method**: **VADER (Valence Aware Dictionary and sEntiment Reasoner)**  
2. **Machine Learning-Based Method**: **Logistic Regression**  

By comparing both techniques, we aim to evaluate their strengths, weaknesses, and real-world applicability.

---

## **Installation & Setup**  
### **To run this project, follow these steps:**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/MohammadA98/SentimentLabelledSentences.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd SentimentLabelledSentences
   ```
3. **Run the Jupyter Notebook** (ensure you have Jupyter installed):
   - Open Jupyter Notebook and click `Run All`, or  
   - Run the following command in the terminal:
     ```bash
     jupyter nbconvert --to notebook --inplace --execute sentiment.ipynb
     ```
   This will execute all notebook cells, install required libraries, and display results.
4. **(Optional)** Extract the real-life experiment dataset:

      The tweets.csv file is large, so a compressed version (tweets_compressed.zip) is included instead. Extracting this file is only necessary if you want to run the real-life experiment portion of the code. Otherwise, you can proceed without it.

      If needed, extract the dataset using:

      ```bash
      unzip tweets_compressed.zip
      ```
      This will extract tweets.csv into the project directory (please rename the file to "tweets.csv").

---

## **Project Objectives**  
This project explores sentiment analysis by:  
✔ **Preprocessing** and cleaning raw text data.  
✔ **Performing Exploratory Data Analysis (EDA)** to understand sentiment distribution.  
✔ **Building and evaluating sentiment classification models**.  
✔ **Comparing lexicon-based and ML-based models for real-world sentiment analysis**.  
✔ **Experimenting on real-world data**, such as:  
   - Sentiment of each tweet in a large collection dataset.

---

## **Dataset Information**  
The dataset contains **sentiment-labeled reviews** from multiple sources:  

| **Source** | **Description** |
|------------|----------------|
| **Amazon Reviews** | User feedback on various products. |
| **IMDB Reviews** | Movie reviews from online users. |
| **Yelp Reviews** | Restaurant and service reviews. |
| **Tweets** | Over a million and a half tweets. |

Each review is labeled as **positive (1) or negative (0)** for supervised learning.

---

## **Methods Used**  
This project incorporates:  
- **Natural Language Processing (NLP)**
- **Supervised Machine Learning**
- **Feature Engineering (TF-IDF)**
- **Sentiment Lexicon Analysis (VADER)**
- **Model Evaluation (ROC Curve, AUC, Classification Reports, etc.)**

---

## **Technologies & Tools**  
- **Python**
- **NLTK** (Natural Language Toolkit)  
- **scikit-learn** (Machine Learning)  
- **Matplotlib & Seaborn** (Data Visualization)  
- **Jupyter Notebook**  

---

## **Contributors**  
### **Mohammad Alhabli**  
- **GitHub**: [MohammadA98](https://github.com/MohammadA98)  
- **LinkedIn**: [Mohammad Alhabli](https://www.linkedin.com/in/mohammad-a-900abb18b/)  

### **Ali Azizi**  
- **GitHub**: [al1az1z1](https://github.com/al1az1z1)  
- **LinkedIn**: [Ali Azizi](https://www.linkedin.com/in/al1az1z1)

---

## **License**  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
