# TDS_Project1
### Project Overview - 
Collected comprehensive GitHub user data in Shanghai with 200+ followers, providing insights into user profiles, activity, and engagement.
Analyzed data to identify correlations between bio length, followers, and other attributes, revealing factors contributing to follower growth.
Results offer practical recommendations for developers to boost engagement and build a larger follower base.

1. Explanation of Data Scraping - This project used GitHub’s API to collect data for users located in Shanghai with over 200 followers. I utilized the requests library to retrieve user details and repository data, filtering and structuring responses using custom Python functions. The data was saved into two CSV files, users.csv and repositories.csv, containing user profiles and repository statistics, respectively. The code processes each user’s bio, public repositories, follower counts, and more, aggregating up to 500 repositories per user while adhering to GitHub's API limits.

2. Interesting Finding - Developers with bio lengths of around 15-25 words often have higher followers, suggesting an ideal range for bio descriptions. Longer bios may indicate a stronger, more engaging presence that attracts followers, particularly if they highlight specific skills or projects.

3. Actionable Recommendation - Developers can improve engagement by crafting clear and concise bios within 15-25 words. Emphasizing relevant skills and projects in this range may lead to increased follower counts, suggesting that strategic bio descriptions play a key role in audience growth.

I obtained the data using the GitHub API, writing a Python script to automate user and repository collection. This script iterates over each user, retrieving profile data and repository details, processing information such as bio content, followers, and repository metadata. I used requests to interact with GitHub’s API and saved the output in CSV format for analysis. Data cleaning and preparation were performed in Excel, where I used pivot tables for ordering and quick aggregations. For more complex queries, like analyzing bio length and correlation with followers, I worked in Jupyter Notebook. Using both Excel and Jupyter enabled me to analyze trends effectively and test different hypotheses about what contributes to higher follower counts.
