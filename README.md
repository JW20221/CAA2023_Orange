# CAA2023_Orange

## Project： Home Assistant Panel
---

## Table of Contents
0. Team participant
1. Description
2. Approach
3. Results
4. Video
---

## 0. Team participant
Jingmin Wang

---

## 1. Description
To improve one's foreign language level, reading text suit for the reader's level is an efficient way. This project built a model for English speakers that predicts the difficulty of a French written text. This can be used in a recommendation system to recommend texts for readers.

---

## 2. Approach
To find the best model for French level detection, I followed these steps:

1. **Text Preparation**. During text preparation, French sentences were tokenized. Data cleaning was also conducted in this step if needed.
2. **Text Representation**.  During this step, text data was represented numerically for further process. I tryed Bag of Words, tf-idf, and Doc2Vec. I choose Tf-idf based on the performance and convenience.
3. **Text Classification**. There are different models for text classification. The commonly used ones include: Logistic regression, KNN, Decision Tree, Random Forest, and LinearSVC. In the code, I compared the performance of these models and found the results below.

---

## 3. Results table
