Google Play Store Apps & Reviews Analytics Dashboard

## 📌 Project Overview
This project analyzes Google Play Store apps and user reviews to uncover insights about:
- Most popular app categories
- Free vs Paid app distribution
- Rating trends
- Install patterns by category
- Sentiment analysis from user reviews
- Revenue estimation by category
- App update trends over time

A dashboard is created using Plotly (interactive HTML) and a final combined dashboard image (PNG).

---

## 🎯 Objectives
- Perform data cleaning and preprocessing on Play Store datasets
- Generate meaningful visualizations for business insights
- Apply sentiment analysis on user reviews using VADER
- Create an interactive dashboard using Plotly HTML
- Save all charts as PNG outputs
- Combine all PNG plots into one final dashboard image

---

## 🗂 Dataset Used
- **Play Store Data.csv**
- **User Reviews.csv**

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly
- NLTK (VADER Sentiment Analyzer)
- Scikit-learn
- Google Colab / Jupyter Notebook
- Git & GitHub

---

## 🔍 Key Steps Performed
### 1. Data Cleaning
- Removed null ratings
- Filled missing values using mode
- Removed duplicates
- Converted columns to correct data types
- Converted installs and price into numeric format
- Converted app size into MB

### 2. Feature Engineering
- `Log_Installs`, `Log_Reviews`
- `Rating_Group`
- `Revenue = Price × Installs`
- Extracted `Year` from last updated date

### 3. Sentiment Analysis
- Applied VADER sentiment scoring on translated user reviews
- Created `Sentiment_Score` column

### 4. Data Visualization (10 Charts)
1. Top Categories on Play Store  
2. App Type Distribution (Free vs Paid)  
3. Rating Distribution  
4. Sentiment Distribution  
5. Installs by Category  
6. Updates per Year  
7. Revenue by Category  
8. Top Genres  
9. Impact of Last Update on Rating  
10. Ratings for Paid vs Free Apps  

---

## 📈 Outputs
All outputs are saved inside the project folder:

### 📁 `outputs/`
- All PNG plots
- `Dashboard.png` (Final combined dashboard)

### 📁 `html_outputs/`
- Interactive Plotly charts (`.html`)
- `Dashboard.html` (Interactive dashboard)

---

## 🌐 Live Website (GitHub Pages)
After enabling GitHub Pages, the dashboard can be accessed here:

👉 **Live Link:** `PASTE_YOUR_GITHUB_PAGES_LINK_HERE`

---
## Google Colab
Google Colab Link : https://colab.research.google.com/drive/1Xx_3fljri8CL1PFw1yI3a5WtFjw-2fs6?usp=sharing

