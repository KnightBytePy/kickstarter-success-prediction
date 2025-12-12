# 🚀 Kickstarter Success Prediction & Clustering

**Data: ** https://webrobots.io/kickstarter-datasets/ - I downloaded the csv zip which has 80+ kickstarter CSVs then looped 
---

## 🔹 Project Overview
Predict whether a Kickstarter project will **succeed or fail** using only launch-time information, and group projects into meaningful clusters to uncover patterns.  

**Tasks:**
1. **Classification:** Predict success/failure at launch.  
2. **Clustering:** Discover campaign groupings and insights.  

---

## 📊 Data & Features
- **Source:** Kickstarter dataset (2025-11-12 snapshot)  
- **Filtered:** Only `successful` or `failed` campaigns  
- **Launch-time features used:**
  - Goal amount, campaign duration, preparation time  
  - Category / main_category, country, currency  
  - Title & blurb length  
- **Excluded:** Pledged amount, backers, updates (post-launch data)  

---

## 🛠 Tech Stack
- **Python:** ML & data analysis  
- **Pandas / NumPy:** Data wrangling  
- **Scikit-learn:** Logistic Regression, Random Forest, KMeans  
- **Matplotlib / Seaborn:** Visualizations  

---

## ⚡ Key Steps
1. Merge & clean CSV files → sort chronologically  
2. Feature engineering (campaign_days, prep_days, text lengths)  
3. Train/Test split **without shuffling**  
4. Build & evaluate classification model  
5. Apply KMeans clustering → analyze cluster characteristics  

---

## 📈 Results
- **Classification:** Predicts success with high accuracy at launch  
- **Clustering:** Reveals actionable project groupings for strategy insights  

**Business Impact:** Helps creators and Kickstarter optimize campaign setup, funding goals, and promotion strategies before launch.  

---

## 🚀 Usage
```bash
# Clone repo
git clone https://github.com/yourusername/kickstarter-success-prediction.git

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Run analysis
python kickstarter_analysis.py
