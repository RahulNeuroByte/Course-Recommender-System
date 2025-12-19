
# 🎓 Course Recommendation System using Udemy Dataset

This project focuses on building a **content-based course recommendation system** using the Udemy dataset. It combines **Exploratory Data Analysis (EDA)** with **Natural Language Processing (NLP)** techniques such as **text vectorization** and **cosine similarity** to recommend similar courses based on course titles.

The project also answers multiple analytical and business-oriented questions related to courses, subscribers, pricing, duration, and popularity.

---

## 📌 Project Objectives

- Analyze Udemy courses across multiple dimensions such as subjects, price, subscribers, and duration
- Identify trends and patterns in course creation and user engagement
- Build a **recommendation system** using course titles
- Recommend relevant courses using **vectorized text similarity**
- Extract meaningful insights to support decision-making

---

## 🗂 Dataset Information

- **Source:** Udemy Course Dataset
- **Key Features:**
  - Course Title
  - Subject / Category
  - Price
  - Number of Subscribers
  - Number of Reviews
  - Number of Lectures
  - Content Duration
  - Level
  - Published Year
  - Paid / Free Indicator

---

## 🧠 Recommendation System Approach

The recommendation system is built using the following steps:

1. **Text Preprocessing**
   - Cleaning course titles
   - Lowercasing
   - Removing stopwords

2. **Vectorization**
   - Using **CountVectorizer / TF-IDF Vectorizer**
   - Converting text into numerical vectors

3. **Similarity Measurement**
   - Applying **Cosine Similarity**
   - Identifying courses with the highest similarity scores

4. **ID-Based Recommendation**
   - Using course index/ID to fetch and recommend similar courses

---

## 🔍 Questions Solved & Analysis

### 📘 Course Title Analysis
- Most frequent words in course titles
- Longest and shortest course titles
- Building recommendation systems using title similarity
- Most famous courses based on number of subscribers

---

### 📚 Subjects / Category Analysis
- Distribution of subjects
- Number of courses per subject
- Subject distribution across years
- Number of subscribers per subject
- Most popular subject based on enrollments

---

### 📆 Published Year Analysis
- Number of courses published per year
- Year with the highest number of courses
- Trend analysis of course creation over time

---

### 🎯 Course Levels Analysis
- Total number of course levels
- Distribution of courses by level
- Subjects with the highest number of levels
- Subscribers per course level
- Courses count per level

---

### ⏱ Duration of Courses
- Courses with the highest duration (paid and free)
- Relationship between course duration and popularity
- Duration vs number of subscribers

---

### 👥 Subscribers Analysis
- Courses with the highest number of subscribers
- Average number of subscribers
- Subscribers per subject
- Subscribers trend per year

---

### 💰 Price Analysis
- Average price of courses
- Minimum and maximum course price
- Estimated Udemy revenue
- Most profitable courses

---

### 🔗 Correlation Analysis
Analyzed the relationship between number of subscribers and:
- Number of reviews
- Course price
- Number of lectures
- Content duration

---

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
  - CountVectorizer / TF-IDF
  - Cosine Similarity
- **Jupyter Notebook**

---

## 📈 Key Insights

- Course titles play a crucial role in recommendations
- Certain subjects consistently attract more subscribers
- Free and low-priced courses often have higher enrollments
- Course duration and number of lectures impact user interest
- Strong correlation between reviews and subscribers

---

## 🚀 Future Enhancements

- Add user-based collaborative filtering
- Improve NLP preprocessing (lemmatization, n-grams)
- Deploy as a web application using Flask
- Add real-time recommendations
- Include user ratings and feedback

---

## 📌 Conclusion

This project demonstrates how **data analysis and machine learning** can be used to build an effective recommendation system. By leveraging text similarity and exploratory analysis, it provides both **actionable insights** and **personalized recommendations**, making it valuable for learners and platform providers alike.

---

## ⭐ If you like this project
Give it a star ⭐ and feel free to fork or contribute!
