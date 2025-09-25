#  Google Play Store Apps Analysis

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Google Play Store dataset**.  
The goal is to uncover insights about app categories, installs, ratings, reviews, and pricing trends that can help developers and businesses make better decisions.

---

##  Dataset
- **Source**: [Google Play Store Dataset] 
- **Format**: CSV file (`googleplaystore.csv`)  
- **Size**: ~10,000+ apps with 13 features  

### Key Features:
- `App` → App name  
- `Category` → Category of the app  
- `Rating` → Average user rating  
- `Reviews` → Number of reviews  
- `Size` → Size of the app  
- `Installs` → Number of installs  
- `Type` → Free or Paid  
- `Price` → Price in USD  
- `Content Rating` → Age group suitability  
- `Genres` → App genres  

---

##  Tools & Libraries
- **Python**  
- **Jupyter Notebook**  
- **Libraries**: pandas, numpy, matplotlib, seaborn  

---

##  Key Steps in Analysis
1. Data Cleaning  
   - Handled missing values  
   - Converted columns (Reviews, Installs, Price, Size) into numeric format  
   - Removed duplicates  

2. Exploratory Data Analysis (EDA)  
   - Distribution of ratings, installs, and prices  
   - Category-wise comparisons  
   - Free vs Paid apps analysis  
   - Correlation heatmap  

3. Insights & Visualizations  
   - Top categories by app count, installs, and reviews  
   - Top 10 most installed and reviewed apps  
   - Price distribution of paid apps  
   - Content rating distribution  
   - App size vs ratings  

---

##  Key Insights
- **Games & Communication** dominate installs and reviews.  
- **Education & Events apps** receive the highest ratings.  
- **Most apps are free**, with paid apps being a small fraction.  
- **Reviews strongly correlate with installs** – popular apps get more reviews.  
- **App size does not strongly affect ratings**, proving quality matters more than size.  
- **Content Rating** shows most apps are made for "Everyone".  

