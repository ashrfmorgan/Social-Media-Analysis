# Social Media Analytics Project - Digital Egypt Pioneers Initiative (DEPI)
An in-depth data analysis project focused on analyzing social media data to extract valuable insights and create an **interactive dashboard** that empowers businesses, influencers, and marketers to make **data-driven decisions**. This project was completed as part of the **Data Engineering Track** in the **Digital Egypt Pioneers Initiative(DEPI)**.

# Table of Contents  

* [Contributors](#Contributors) 
* [Brief](#Brief)
* [How It Works](#HowItWorks)
* [DataSet](#DataSet)
* [Project Goal](#ProjectGoal)
* [Our Team](#OurTeam)
* [Tech Stack](#TechStack)
* [Tools](#Tools)  
* [Key Achievements](#KeyAchievements)  
* [Key Findings](#KeyFindings)  
* [Key Recommendations](#KeyRecommendations)
* [Acknowledgments](#Acknowledgments)  
* [Future Work](#FutureWork)  



#  Contributors

* [Ashraf Morgan](https://github.com/ashrfmorgan)

* [Ibrahim Hegazi](https://github.com/Ibrahim-Hegazi)

* [Mahmoud Osama](https://github.com/MahmoudOsamax)

* [Yousef Elsbaey]()

* [Ammar Yasser](https://github.com/Ammaryasser4)

* [Amr Khaled](https://github.com/GOAT-AK)

# Brief
This project focuses on analyzing social media data to provide actionable insights for businesses, influencers, and marketers. By leveraging interactive dashboards, the project helps optimize social media strategies, drive audience engagement, and enable data-driven decision-making. This initiative was developed as part of the DEPI Data Engineering Track, ranking in the top 20 participating teams.

# How It Works
1. **Data Loading and Preparation**:  
   The script starts by loading multiple
   `PostDimension.csv`, `UserDimension.csv`, and `SentimentFact.csv`, using Pandas. The data is cleaned, merged, and saved into a unified dataset (`sentiment_factDEPI.csv`) for streamlined analysis.

2. **Exploratory Data Analysis (EDA)**:  
   Key insights are derived through EDA:
   - Checking for missing values to ensure data quality.
   - Identifying unique platforms and sentiment categories.
   - Analyzing the distribution of platforms and their associated sentiments.

3. **Data Visualization**:  
   The script generates insightful visualizations to uncover trends:
   - **Sentiment Distribution by Platform**: A bar chart shows the breakdown of sentiment categories across platforms.
   - **Follower Count vs. Sentiment Score**: A scatter plot highlights the relationship between followers and sentiment scores.
   - **Sentiment by Location**: A bar chart reveals sentiment distributions across locations.
   - **Time-Based Sentiment Trends**: A line plot illustrates daily changes in average sentiment scores.

4. **Output**:  
   The processed dataset and visualizations are saved as files for further analysis and reporting.
# DataSet
- The dataset used in this project is the [Social Media Sentiments Analysis Dataset](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset/data)  from Kaggle
  
# Project Goals
- Extract insights from social media data across multiple platforms
- Provide key metrics and trends in an interactive Power BI dashboard
- Empower data-driven strategies for audience targeting and engagement

# Our Role
* [Amr Khaled](https://www.linkedin.com/in/amr-khaled03/) (Data Collecting and Preprocessing) 
* [Mahmoud Osama](https://www.linkedin.com/in/mahmoud-osama-78aaab260/) (EDA)
* [Ashraf Morgan](https://www.linkedin.com/in/ashrf-morgan-2a6909254/)
 (Data Visualization)
* [Ammar Yasser](https://www.linkedin.com/in/ammar-yasser-b99338325/) (Data Visualization)
* [Ibrahim Hegazi](https://www.linkedin.com/in/ibrahim-hegazi-9ba3a5269/) (Data Visualization) 
* [Yousef Alsebaey](https://www.linkedin.com/in/yousef-alsebaey-741ba9114/) (Project Insights, Story Telling)

# Tech Stack
- **Python**: EDA
- **Power Query**: Data cleaning
- **Power BI**: Data visualization

# Tools

I. Jupyter Notebook

II. Python 3.x

III. pandas

IV. matplotlib

V. seaborn

# Key Achievements
- Developed dynamic dashboards with insights for companies and influencers
- Optimized database schema for efficient querying
- Conducted extensive EDA to reveal sentiment patterns
- Analyzed data across 5 social media platforms

# Key Findings
- Best cities for targeted content marketing
- Best platforms for higher reach and positive feedback

# Key Recommendations
- Target high-engagement platforms (e.g., Snapchat, TikTok)
- Engage influencers from Tokyo, New York, and Cairo
- Launch campaigns from May to July
 
# Acknowledgments
- This project was made possible through the support and guidance of the [Digital Egypt Pioneers Initiative (DEPI)](https://www.linkedin.com/company/digital-egypt-pioneers-initiative-depi/posts/?feedView=all) and the collaborative efforts of my peers and mentor.
- Special thanks to:

   I. DEPI Organizers for providing a structured learning track and valuable resources.

   II. Mentor [Mohamed Abdelmwla](https://www.linkedin.com/in/mohamed-abdelmawla-85219b56/) for his continuous guidance throughout the Data Engineering track.

   III. My Team Members for their collaboration and dedication to achieving project goals.
  -  [Amr Khaled](https://www.linkedin.com/in/amr-khaled03/)
  
  -  [Mahmoud Osama](https://www.linkedin.com/in/mahmoud-osama-78aaab260/)
   
  -  [Ashraf Morgan](https://www.linkedin.com/in/ashrf-morgan-2a6909254/)
  
  -  [Ammar Yasser](https://www.linkedin.com/in/ammar-yasser-b99338325/)
  
  -  [Ibrahim Hegazi](https://www.linkedin.com/in/ibrahim-hegazi-9ba3a5269/)
  
  -  [Yousef Alsebaey](https://www.linkedin.com/in/yousef-alsebaey-741ba9114/)
  
- Your support and encouragement were instrumental in the successful completion of this project.

## Future Work
- Acquire datasets with follow/unfollow dates and engagement times
- Incorporate AI to optimize posting times for better engagement
