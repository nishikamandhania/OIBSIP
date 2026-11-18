# Google Play Store Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Google Play Store ecosystem using Python. It explores app categories, ratings, installations, app sizes, pricing patterns, and user review sentiment to identify meaningful market trends and insights.

The objective is to understand app performance, user preferences, market competition, and opportunities that can help app developers make data-driven decisions.

## Objectives

- Analyze the distribution of apps across different categories.
- Explore app ratings and average ratings by category.
- Study the relationship between app size and installations.
- Compare free and paid applications.
- Analyze paid app pricing patterns.
- Estimate potential revenue across app categories.
- Perform sentiment analysis on user reviews.
- Identify categories with positive and negative user feedback.
- Create interactive visualizations using Plotly.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- Plotly
- Jupyter Notebook

## Datasets

This project uses two datasets:

1. **Google Play Store Apps Dataset** – Contains app details such as name, category, rating, size, installations, type, price, content rating, and genres.
2. **Google Play Store User Reviews Dataset** – Contains user reviews and sentiment-related information.

**Dataset Source:** Add the original Kaggle dataset link here.

## Project Workflow

### 1. Data Loading and Cleaning
- Loaded the Apps and User Reviews datasets.
- Checked missing values and duplicate records.
- Removed duplicate and invalid records.
- Handled missing values where appropriate.
- Converted installation counts and prices into numeric formats.
- Created additional columns for app size, installations, and price analysis.

### 2. Category Analysis
- Analyzed app distribution across categories.
- Identified categories with the highest number of applications.
- Visualized the top 10 app categories.

### 3. Ratings Analysis
- Explored the distribution of app ratings.
- Calculated average ratings by category.
- Compared ratings of free and paid applications.

### 4. Size and Installation Analysis
- Analyzed app sizes across categories.
- Created a scatter plot to study the relationship between app size and installations.
- Calculated Pearson and Spearman correlation coefficients.

### 5. Pricing and Revenue Analysis
- Compared free and paid applications.
- Analyzed the distribution of paid app prices.
- Calculated estimated revenue by category using listed prices and reported installations.

### 6. Sentiment Analysis
- Cleaned user review data.
- Used TextBlob to calculate review polarity.
- Classified reviews as Positive, Negative, or Neutral.
- Compared sentiment distribution across app categories.
- Compared TextBlob sentiment classifications with the original sentiment labels.

### 7. Data Visualization
Created visualizations using Matplotlib, Seaborn, and Plotly, including:
- Category distribution charts
- Rating distribution charts
- App size and installation scatter plot
- Pricing analysis charts
- Revenue comparison charts
- Sentiment distribution charts
- Interactive category analysis using Plotly

## Key Findings

- **Category Distribution:** FAMILY has the highest number of apps, with 1,943 applications.
- **Installations:** GAME leads in total installations, with approximately 31.54 billion.
- **Ratings:** The average app rating is approximately 4.19.
- **Free vs Paid:** The dataset contains 9,592 free apps and 765 paid apps.
- **App Size:** App size has a weak positive relationship with installations (Pearson correlation: 0.169).
- **Sentiment:** Approximately 64.04% of analyzed reviews are positive, 21.29% negative, and 14.67% neutral.
- **Category Sentiment:** GAME has the highest negative-review proportion among categories, at approximately 35.66%.

## Business Insights for App Developers

1. **Understand Market Competition:** FAMILY has the largest number of applications, while GAME leads in total installations. Developers should consider both competition and market demand before choosing a category.

2. **Prioritize User Experience:** Although most reviews are positive, some categories have a relatively high proportion of negative feedback. Developers should focus on app performance, usability, and user feedback.

3. **Focus on Value:** App size alone is not a strong predictor of installations. Developers should prioritize useful features, customer needs, and an appropriate pricing strategy.

## Limitations

- Some app ratings and app sizes were unavailable in the dataset.
- Installation counts are approximate values rather than exact figures.
- Estimated revenue is calculated using listed prices multiplied by reported installations. It does not represent actual earnings.
- TextBlob may not fully understand sarcasm, context, or complex expressions.
- Category-wise sentiment analysis excludes apps with ambiguous category mappings.
- Some category-level results are based on relatively small review samples.

## Conclusion

This project demonstrates how Python can be used to analyze the Google Play Store ecosystem and extract meaningful business insights.

Through data cleaning, exploratory analysis, visualization, and sentiment analysis, the project highlights important patterns in app categories, ratings, installations, pricing, and user feedback.

It provides practical experience in data analysis and demonstrates how data-driven insights can support better app development and business decisions.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Correlation Analysis
- Sentiment Analysis
- Business Insight Generation
- Interactive Visualization

---

**Project Track:** Data Analytics  
**Program:** Oasis Infobyte Student Internship Program (SIP)  
**Task:** Level 2 – Task 4: Google Play Store Analysis
