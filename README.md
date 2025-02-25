# Simulated-Social-Media-Engagement-Analysis
## Using Python Clean &amp; Analyze Social Media <br>

### 🔍 Objective<br>

This project analyzes simulated social media engagement data to gain insights into user interactions across different content categories. Using Python, Pandas, NumPy, Seaborn, and Matplotlib, we generate random social media posts, visualize engagement trends, and identify the most popular categories.<br>

### 📂 Project Overview<br>
1️⃣ Data Generation<br>
Created a synthetic dataset with 500 random posts using:<br>
pandas.date_range() for random timestamps.<br>
random.choice() for content categories.<br>
np.random.randint() for likes (0–10,000).<br>
2️⃣ Data Cleaning & Transformation<br>
Removed duplicate entries.<br>
Converted the Date column to datetime format.<br>
Ensured Likes column is an integer.<br>
3️⃣ Exploratory Data Analysis (EDA)<br>
✅ Histogram of Likes – Understand engagement distribution.<br>
✅ Boxplot of Likes per Category – Identify high-engagement categories and outliers.<br>
✅ Mean Likes per Category – Discover which content types perform best.<br>

### 📊 Visualizations<br>
Histogram of Likes Distribution<br>
Boxplot of Category-wise Likes<br>


### 📌 Key Findings<br>
🔹 Engagement varies by category – Some categories such as Health, Food, Fitness receive significantly more likes.<br>
🔹 Most posts receive moderate engagement, but a few go viral (long-tail distribution).<br>
🔹 Outliers exist, meaning some content gains extreme popularity.<br>

### 🚀 Future Improvements <br>
Real Data Integration: Use Twitter sentiment data for real-world insights.<br>
Sentiment Analysis: Examine how content tone influences engagement.<br>
Time-Series Forecasting: Predict best times for posting based on engagement trends.<br>

### 🛠️ Technologies Used <br>
Library	Purpose<br>
pandas	Data handling & transformation<br>
numpy	Random data generation<br>
seaborn	Data visualization<br>
matplotlib.pyplot	Graph plotting<br>
random	Simulating categorical data<br>

### 📂 Project Structure<br>
📦 Social-Media-Engagement-Analysis<br>
│-- 📜 README.md<br>
│-- 📜 social_media_analysis.ipynb<br>
│-- 📂 images/<br>
│   │-- histogram.png<br>
│   │-- boxplot.png<br>
│-- 📂 data/<br>
│   │-- generated_data.csv<br>


### 📌 How to Run<br>
1️⃣ Clone this repository<br>
git clone https://github.com/anniennanda/Simulated-Social-Media-Engagement-Analysis.git<br>
cd Simulated-Social-Media-Engagement-Analysis<br>

2️⃣ Install dependencies<br>
pip install pandas numpy matplotlib seaborn<br>

3️⃣ Run the Jupyter Notebook<br>
jupyter notebook SocialMediaDataAnalysis.ipynb<br>











