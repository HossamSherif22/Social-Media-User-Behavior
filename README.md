# Social Media & User Behavior — Global 2026

An exploratory data analysis project focused on how users interact with social media platforms across demographics, engagement behavior, lifestyle patterns, and wellbeing-related indicators.

This project uses Python-based data analysis to study user activity such as screen time, session behavior, content preferences, engagement levels, spending behavior, and addiction-related trends. The notebook is designed to turn raw behavioral data into clear visual insights.

## Project Overview

The analysis explores questions such as:

- How does social media usage vary across age groups, gender, country, and occupation?
- Which platforms and content types are most common among users?
- How are engagement metrics like likes, comments, shares, and followers distributed?
- Is there a relationship between screen time, sleep, productivity, and addiction level?
- How do account age and account creation dates relate to user behavior?

## Datasets

This project uses two CSV files:

### 1. `social_media_user_behavior.csv`

The main dataset contains user-level behavioral and profile information, including:

- Demographics: `age`, `age_group`, `gender`, `country`, `occupation`, `education_level`, `income_bracket`
- Platform behavior: `primary_platform`, `preferred_content_type`, `primary_device`, `usage_purpose`
- Engagement: `posts_per_week`, `likes_per_day`, `comments_per_day`, `shares_per_week`, `followers_count`, `engagement_rate_pct`
- Lifestyle and wellbeing: `sleep_hours_per_night`, `addiction_level_1_to_10`, `productivity_impact`, `self_reported_mental_health_effect`
- Account features: `account_created_date`, `account_age_years`, `is_verified_account`, `is_content_creator`

### 2. `platform_statistics_2026.csv`

A supporting dataset containing platform-level statistics such as:

- Monthly active users
- Year-over-year growth
- Average daily time spent
- Primary age group
- Content format
- Engagement rate
- Social commerce adoption

## Project Structure

```text
Social Media & User Behavior — Global 2026/
├── README.md
├── social_media_user_behavior.csv
├── platform_statistics_2026.csv
└── ٍSocial Media.ipynb
```

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Workflow

The notebook includes:

1. Data loading and first inspection
2. Data type correction, including converting `account_created_date` to datetime
3. Missing-value and duplicate checks
4. Numerical and categorical summaries
5. Side-by-side visualizations for numeric and categorical variables
6. Social-media-focused EDA sections:
   - User demographics
   - Platform usage
   - Engagement analysis
   - Lifestyle and wellbeing trends
   - Account and time-based trends
   - Target-focused insights using `addiction_level_1_to_10`

## Example Topics Explored

- Distribution of user age and age groups
- Most used platforms and devices
- Engagement behavior across users
- Social commerce and influencer-related behavior
- Relationship between screen time and addiction level
- Sleep patterns across addiction levels
- Average addiction level by platform

## Key Features of This Project

- Clean and structured EDA workflow
- Professional summary tables for categorical and numeric variables
- Compact subplot layouts to save space in notebook output
- Domain-based analysis tailored to social media behavior
- Clear visual storytelling for portfolio presentation

## How to Run

1. Open the notebook `ٍSocial Media.ipynb`
2. Make sure the required libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Run the notebook cells in order

## Potential Improvements

- Add a dashboard version using Power BI, Tableau, or Plotly
- Build predictive models for addiction level or purchase behavior
- Compare user-level behavior with platform-level statistics
- Add a formal insights and recommendations section

## Author

Created as a data analysis portfolio project to practice:

- data cleaning
- exploratory data analysis
- feature grouping
- data visualization
- insight communication

## License

This project is for educational and portfolio purposes.
