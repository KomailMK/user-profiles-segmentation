# User Profiling and Segmentation

This project involves user profiling and segmentation based on a dataset containing various user attributes. The aim is to understand user behavior and preferences to tailor strategies for improved customer service, personalized marketing, and effective product recommendations.

## Dataset
The dataset `user_profiles_for_ads.csv` contains the following columns:
- User ID: Unique identifier for each user
- Age: Age range of the user
- Gender: Gender of the user
- Location: User’s location type (Urban, Suburban, Rural)
- Language: Primary language of the user
- Education Level: Highest education level achieved
- Likes and Reactions: Number of likes and reactions a user has made
- Followed Accounts: Number of accounts a user follows
- Device Usage: Primary device used for accessing the platform (Mobile, Desktop, Tablet)
- Time Spent Online (hrs/weekday): Average hours spent online on weekdays
- Time Spent Online (hrs/weekend): Average hours spent online on weekends
- Click-Through Rates (CTR): The percentage of ad impressions that lead to clicks
- Conversion Rates: The percentage of clicks that lead to conversions/actions
- Ad Interaction Time (sec): Average time spent interacting with ads in seconds
- Income Level: User’s income level
- Top Interests: Primary interests of the user

## How to Run
1. Clone the repository
2. Ensure you have the required libraries installed (pandas, matplotlib, seaborn, scikit-learn)
3. Run the Jupyter Notebook `user_profiles_segmentation.ipynb`

## Results
The results include various visualizations and a clustering model that segments users into distinct groups for targeted ad campaigns.
