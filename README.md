# 🛍️ Amazon Product Review & Pricing Analysis using Python

## 📘 Project Overview
This project focuses on analyzing Amazon product data to uncover insights about product pricing, discounts, ratings, and customer sentiment.  
Using Python’s data analysis and visualization libraries, I explored patterns that reveal how pricing strategies and customer reviews influence product performance across categories.

---

## 🎯 Business Objective
To analyze Amazon product data and derive actionable insights that can help improve:
- Pricing and discount strategies  
- Product category performance  
- Customer satisfaction patterns through reviews and ratings  

---

## 🧩 Dataset Description
The dataset contains detailed information about Amazon products, including pricing, ratings, and textual reviews.  

**Columns:**
`product_id`, `product_name`, `category`, `discounted_price`, `actual_price`, `discount_percentage`,  
`rating`, `rating_count`, `about_product`, `user_id`, `user_name`,  
`review_id`, `review_title`, `review_content`, `img_link`, `product_link`

---

## 🧮 Methodology & Workflow

### 1. 📚 Import Libraries
Used the following Python libraries:
`pandas`, `numpy`, `seaborn`, `matplotlib`, `textblob`, `wordcloud`, `sklearn`, `re`, and `collections.Counter`

### 2. 📂 Data Loading and Exploration
- Loaded dataset from Google Drive into Google Colab  
- Explored structure, shape, and column data types  
- Performed initial observation for inconsistencies and null values  

### 3. 🧼 Data Cleaning & Preprocessing
- Changed data types for numerical and categorical columns  
- Handled missing values appropriately  
- Removed duplicate records  
- Cleaned text data (regex-based cleaning and normalization)  
- Ensured all numeric fields were properly formatted for analysis  

✅ **Milestone 1:** Dataset successfully cleaned and validated  
✅ **Milestone 2:** No duplicate records found  

### 4. 📊 Descriptive Statistics
- Calculated measures such as mean, median, and standard deviation for key metrics  
- Summarized discount, rating, and price distributions  

### 5. 🔥 Data Visualization
Created clear and meaningful visualizations using Seaborn and Matplotlib:
- Scatter plots (Price vs. Discount, Rating vs. Discount)
- Histograms (Rating, Price distribution)
- Boxplots (Category vs. Ratings)
- Heatmaps (Correlation analysis)
- WordClouds (Most common review keywords)
- Bar charts (Top-rated products and categories)

---

## 🧠 Analytical Questions & Insights

| **Question** | **Analysis Performed** 
|---------------|------------------------
| Q1 | Average rating for each product category 
| Q2 | Top products by rating count in each category 
| Q3 | Distribution of discounted vs. actual prices 
| Q4 | Average discount % by category 
| Q5 | Most popular product names 
| Q6 | Most frequent product keywords (WordCloud) 
| Q7 | Most popular review sentiments 
| Q8 | Correlation between discounted_price and rating 
| Q9 | Top 5 categories with highest average ratings

---

## 🧾 Summary of Findings
- **Pricing Trends:** Average discounts lie between 25–40%; heavy discounts don’t guarantee higher ratings.  
- **Customer Sentiment:** Majority of reviews are positive; sentiment analysis reveals strong product satisfaction in key categories.  
- **Category Insights:** Electronics and Accessories dominate both in ratings and review volume.  
- **Data Integrity:** After cleaning, dataset achieved 100% consistency with no missing or duplicate records.

---

## ⚙️ Tools & Technologies Used
| Category | Tools |
|-----------|--------|
| **Data Handling** | pandas, numpy |
| **Visualization** | seaborn, matplotlib |
| **Text Analysis** | textblob, wordcloud, re, Counter |
| **Preprocessing / Modeling** | sklearn |
| **Environment** | Google Colab, Google Drive |

---

## 📈 Key Visuals (Examples) 
- Average Rating by Category  
- Discount vs Actual Price Scatter Plot  
- WordCloud of Review Keywords  
- Correlation Heatmap  

