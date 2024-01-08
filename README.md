# Youtube-Statistical-Analysis
YouTube Engagement Analysis: Enhancing Content Strategy Through Data

## Project Description:

In this data science and machine learning project, I will delve into the vast world of YouTube content to analyze user engagement, and recommend personalized video suggestions. Leveraging a comprehensive YouTube statistics dataset from Kaggle, our goal is to provide content creators and marketers with actionable insights to optimize their strategies and boost their channel's performance.

**Engagement Analysis:** Analyze metrics such as subscribers, rank, uploads, and views to identify patterns and trends.

**Data Visualization:** Create informative data visualizations and interactive dashboards to present our findings in an engaging and comprehensible manner.

1. **Content Creator Profiling:**
   - Use the 'subscribers' and 'video views' columns to identify top content creators.
   - Group creators by category and country to understand the diversity of content on YouTube.


2. **Performance Metrics Analysis:**
   - Analyze 'subscribers,' 'video views,' and 'uploads' to identify trends and patterns in channel growth.
   - Create visualizations to represent changes over time.


3. **Monetization Insights:**
   - Utilize 'lowest_monthly_earnings' and 'highest_monthly_earnings' to analyze the earnings potential of content creators.
   - Identify factors that contribute to higher earnings.


4. **Audience Engagement and Demographics:**
   - Explore 'Country' and 'Urban_population' to understand the geographic distribution of viewers.
   - Analyze 'Gross tertiary education enrollment (%)' to assess the education level of the audience.


5. **Predictive Modeling:**
   - Build predictive models using historical data to forecast metrics like 'subscribers' and 'video views.'
   - Evaluate the accuracy of the models and make recommendations based on predictions.

By the end of this project, I aim to empower YouTube content creators and marketers with data-driven strategies to enhance user engagement, improve content quality, and give insight on statistical analysis of the last 10 years.

## Plots and Visualizations

### Actual vs Predicted
![Actual vs Predicted](path/to/actual_predicted.png)

### Audience Engagement
![Audience Engagement](path/to/audience_engagement.png)

### Distribution of Views
![Distribution of Views](path/to/distribution_views.png)

### Earnings by Channel Type
![Earnings by Channel Type](path/to/earnings_channeltype.png)

### Earnings by Subscribers
![Earnings by Subscribers](path/to/earnings_subribers.png)

### Earnings by Views
![Earnings by Views](path/to/earnings_views.png)

### Education Enrollment vs Subscribers
![Education Enrollment vs Subscribers](path/to/education_enrollment_subscribers.png)

### Map Plots
![Map Plot 1](path/to/mapplot1.png)
![Map Plot 2](path/to/mapplot2.png)
![Map Plot 3](path/to/mapplot3.png)
![Map Plot 4](path/to/mapplot4.png)

### Rank by Video Category
![Rank by Video Category](path/to/rank_video_category.png)

### Subplot Distribution
![Subplot Distribution](path/to/subplot_distribution.png)

### Top Channels by Country
![Top Channels by Country](path/to/top_channels_country.png)

### Top Content by Subscribers
![Top Content by Subscribers](path/to/top_content_subscribers.png)

### Top Countries by Subscribers
![Top Countries by Subscribers](path/to/top_countries_subscribers.png)


## Conclusion
In this project, I conducted an exploratory data analysis (EDA) and predictive modeling on a dataset containing information about various YouTube channels. The dataset covered a wide range of variables, including channel rankings, subscribers, video views, uploads, and demographic details. The primary objectives were to understand the data, perform necessary preprocessing, conduct an exploratory analysis, and create a predictive model for subscribers based on other channel attributes.

Key Steps and Findings:

Data Cleaning and Preprocessing: Begin by cleaning the dataset, addressing issues like missing values, data types, and scaling. Additionally, converted columns to lowercase and snake case for consistency.

Exploratory Data Analysis (EDA): Conducted EDA to gain insights into the data. Visualized the distribution of key features, such as subscribers and video views, and observed relationships between variables. Notably,  examining demographic factors, such as education enrollment and unemployment rates, and their correlation with subscribers.

Predictive Modeling: To predict subscribers, created a linear regression model. Evaluated the model's performance through cross-validation and visualized the actual vs. predicted subscriber counts.

Challenges:

Predictive modeling presented challenges, as the Mean Squared Error (MSE) values were initially high. Further feature selection and engineering might improve model performance.

In summary, this analysis provides valuable insights into the factors that influence the number of subscribers for YouTube channels. It serves as a foundation for further exploration and model refinement to better understand and predict channel growth on this popular platform.

