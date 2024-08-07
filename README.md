# Youtube-Statistical-Analysis
YouTube Engagement Analysis: Enhancing Content Strategy Through Data

## Project Description:

This data science and machine learning project dives into the vast world of YouTube content to analyze user engagement, and recommend personalized video suggestions. Leveraging a comprehensive YouTube statistics dataset from Kaggle, our goal is to provide content creators and marketers with actionable insights to optimize their strategies and boost their channel's performance.

**Engagement Analysis:** Analyze metrics such as subscribers, rank, uploads, and views to identify patterns and trends.

**Data Visualization:** Create informative data visualizations and interactive dashboards to present our findings in an engaging and comprehensible manner.

### Methods and Techniques

1. **Content Creator Profiling:**
   - Used the 'subscribers' and 'video views' columns to identify top content creators.
   - Grouped creators by category and country to understand the diversity of content on YouTube.


2. **Performance Metrics Analysis:**
   - Analyzed 'subscribers,' 'video views,' and 'uploads' to identify trends and patterns in channel growth.
   - Created visualizations to represent changes over time.


3. **Monetization Insights:**
   - Utilized 'lowest_monthly_earnings' and 'highest_monthly_earnings' to analyze the earnings potential of content creators.
   - Identified factors that contribute to higher earnings.


4. **Audience Engagement and Demographics:**
   - Explored 'Country' and 'Urban_population' to understand the geographic distribution of viewers.
   - Analyzed 'Gross tertiary education enrollment (%)' to assess the education level of the audience.


5. **Predictive Modeling:**
   - Built predictive models using historical data to forecast metrics like 'subscribers' and 'video views.'
   - Evaluated the accuracy of the models and make recommendations based on predictions.

By the end of this project, I aim to empower YouTube content creators and marketers with data-driven strategies to enhance user engagement, improve content quality, and give insight on statistical analysis of the last 10 years.

## Plots and Visualizations

### Actual vs Predicted
![Actual vs Predicted](plots/actual_predicted.png)

### Audience Engagement
![Audience Engagement](plots/audience_engagement.png)

### Distribution of Views
![Distribution of Views](plots/distribution_views.png)

### Earnings by Channel Type
![Earnings by Channel Type](plots/earnings_channeltype.png)

### Earnings by Subscribers
![Earnings by Subscribers](plots/earnings_subribers.png)

### Earnings by Views
![Earnings by Views](plots/earnings_views.png)

### Education Enrollment vs Subscribers
![Education Enrollment vs Subscribers](plots/education_enrollment_subscribers.png)

### Map Plots
![Map Plot 1](plots/mapplot1.png)
![Map Plot 2](plots/mapplot2.png)
![Map Plot 3](plots/mapplot3.png)
![Map Plot 4](plots/mapplot4.png)

### Rank by Video Category
![Rank by Video Category](plots/rank_video_category.png)

### Subplot Distribution
![Subplot Distribution](plots/subplot_distribution.png)

### Top Channels by Country
![Top Channels by Country](plots/top_channels_country.png)

### Top Content by Subscribers
![Top Content by Subscribers](plots/top_content_subscribers.png)

### Top Countries by Subscribers
![Top Countries by Subscribers](plots/top_countries_subscribers.png)


## Conclusion
In this project, I conducted an exploratory data analysis (EDA) and predictive modeling on a dataset containing information about various YouTube channels. The dataset covered a wide range of variables, including channel rankings, subscribers, video views, uploads, and demographic details. The primary objectives were to understand the data, perform necessary preprocessing, conduct an exploratory analysis, and create a predictive model for subscribers based on other channel attributes.

Key Steps and Findings:

Data Cleaning and Preprocessing: Begin by cleaning the dataset, addressing issues like missing values, data types, and scaling. Additionally, converted columns to lowercase and snake case for consistency.

Exploratory Data Analysis (EDA): Conducted EDA to gain insights into the data. Visualized the distribution of key features, such as subscribers and video views, and observed relationships between variables. Notably,  examining demographic factors, such as education enrollment and unemployment rates, and their correlation with subscribers.

Predictive Modeling: To predict subscribers, created a linear regression model. Evaluated the model's performance through cross-validation and visualized the actual vs. predicted subscriber counts.

Challenges:

Predictive modeling presented challenges, as the Mean Squared Error (MSE) values were initially high. Further feature selection and engineering might improve model performance.

In summary, this analysis provides valuable insights into the factors that influence the number of subscribers for YouTube channels. It serves as a foundation for further exploration and model refinement to better understand and predict channel growth on this popular platform.

