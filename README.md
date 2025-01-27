# Social Media Sentiment Analysis

## Overview
In the digital era, understanding audience engagement is essential for content creators and marketers. This project analyzes factors influencing retweets and likes on social media posts using **R Programming**. By leveraging statistical methods and predictive modeling, we aim to provide actionable insights for optimizing content strategies.

---

## Problem Statement
The goal of this analysis is to answer the following:
1. What are the central tendencies (mean, median, mode) of retweets?
2. How do variations in likes and retweets correlate?
3. What relationships exist between retweets and other variables (e.g., month and likes) using linear regression?
4. Can we predict future retweets based on historical data?

---

## Solution Workflow
The project followed these key steps:
1. **Data Collection:** Utilized a dataset containing social media metrics like retweets, likes, and month of posting.
2. **Data Preprocessing:** Handled missing values, transformed categorical data, and normalized numerical features.
3. **Descriptive Statistics:** Explored central tendencies, dispersion metrics, skewness, and kurtosis of retweets.
4. **Data Visualization:** Generated histograms, box plots, and scatter plots for better understanding.
5. **Correlation Analysis:** Evaluated the relationship between retweets and likes.
6. **Regression Analysis:**
   - Simple Linear Regression: Relationship between month and retweets.
   - Multiple Linear Regression: Combined effects of likes and month on retweets.
7. **Model Diagnostics:** Verified assumptions of regression models and identified potential outliers.
8. **Prediction:** Forecasted retweets using trained regression models.
9. **Classical Tests:** Conducted one-sample t-tests, two-sample t-tests, and ANOVA for deeper insights.

---

## Key Insights
- Identified central tendencies and variability in retweets.
- Found a strong correlation between likes and retweets.
- Regression models revealed significant predictors of retweet engagement (likes and posting month).
- Statistical tests showed engagement differences across months.

---

## Tools & Technologies
- **Language:** R Programming
- **Libraries:** ggplot2, dplyr, psych, stats
- **Techniques:** Data preprocessing, regression analysis, data visualization, statistical testing

---

## Dataset Overview
- **Rows:** 732
- **Columns:** 14
- Metrics include retweets, likes, month of posting, and other social media engagement features.

---

## Visualization Examples
### Histogram of Retweets
![Histogram of Retweets]("C:\Users\kavya\OneDrive\Desktop\r programming\Rplot01.png")

### Scatter Plot: Retweets vs. Likes
![Scatter Plot]("C:\Users\kavya\OneDrive\Desktop\r programming\Rplot02.png")

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/kavyak1604/social-media-sentiment-analysis.git
2.Open the project in Rstudio  
3.Install required libraries:  
> install.packages(c("ggplot2", "dplyr", "psych"))

4.Run the script to analyze and visualize the data:
> source("analysis_script.R")

# Conclusion
This project demonstrates how data analysis and statistical techniques can uncover meaningful insights into social media engagement.  
These findings can guide marketers and content creators in crafting strategies to boost audience interaction.

# References
● Data Analysis and Statistics:  
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An Introduction to Statistical
Learning: With Applications in R. Springer.    
- Wickham, H., & Grolemund, G. (2017). R for Data Science. O'Reilly Media.  
● Sentiment Analysis:  
- Liu, B. (2015). Sentiment Analysis: Mining Opinions, Sentiments, and Emotions.  
Cambridge University Press.  
● Regression and Correlation:  
- Kutner, M. H., Nachtsheim, C., & Neter, J. (2005). Applied Linear Statistical Models.  
McGraw-Hill.  
- Schober, P., Boer, C., & Schwarte, L. A. (2018). Correlation coefficients: Appropriate  
use and interpretation. Anesthesia & Analgesia, 126(5), 1763-1768.  
● Data Visualization:  
- Wickham, H. (2016). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag.
- 




