# GitHub API Data Analysis: Stockholm Users with >100 Followers

- **Data Collection Process**: Using the GitHub API, this project collects profile information for GitHub users in Stockholm with over 100 followers and their most recent repositories, storing the data in CSV format for detailed analysis.
- **Interesting Insight**: The MIT, Apache 2.0, and GPL licenses are the top choices among repositories, showing a clear preference for open-source licensing among Stockholm developers.
- **Actionable Recommendation**: To maximize impact, developers in Stockholm should consider enhancing repository documentation and issue-tracking, as these features appear underused despite high follower counts.

## Project Overview
This project provides an analysis of prominent GitHub users in Stockholm, focusing on their profiles and the characteristics of their public repositories. It aims to identify trends, highlight popular practices, and make recommendations based on the data collected.

### Project Structure
- **users.csv**: Contains user data, including fields such as `login`, `name`, `company`, `location`, `email`, `hireable` status, and more.
- **repositories.csv**: Lists each user’s recent repositories (up to 500 per user), including details such as `full_name`, `created_at`, `stargazers_count`, `language`, and `license_name`.
- **README.md**: This file, explaining the project, methodology, and results.
- **Data Collection Code**: (Optional) The code used to fetch and process data, stored here for transparency and reproducibility.

### Methodology
1. **Data Extraction**: 
   - Used the GitHub API to collect data on users in Stockholm with over 100 followers. 
   - Retrieved profile details and up to 500 repositories per user, ensuring comprehensive coverage.
2. **Data Cleaning and Processing**: 
   - Cleaned and standardized fields, particularly `company` names, removing extra whitespace and symbols.
   - Converted boolean fields to `true` or `false`, and handled missing values by using empty strings where necessary.
3. **Data Analysis**: 
   - Calculated statistics, including the most commonly used licenses and primary programming languages.
   - Analyzed engagement metrics like `stargazers_count` and `watchers_count` to identify high-impact repositories.

### Results
- **Top Licenses**: The most popular licenses among Stockholm users are MIT, Apache 2.0, and GPL, reflecting a strong open-source culture.
- **Primary Languages**: JavaScript, Python, and TypeScript are the most frequently used languages, suggesting a high prevalence of web and data science projects.
- **Repository Features**: Many repositories are missing robust documentation and issue-tracking features, even though these could enhance user engagement and project contributions.

### Recommendations
1. **Documentation**: Stockholm developers should prioritize adding detailed documentation to repositories, as projects with documentation tend to receive more engagement.
2. **Issue-Tracking**: Enabling and actively managing issue-tracking could improve collaboration, especially for repositories with high follower counts.
3. **License Choice**: Open-source projects are highly favored; developers should consider including a permissive license to attract more collaborators.

### How to Run the Analysis
1. **Setup**: Clone this repository and ensure that dependencies, such as `pandas`, are installed.
2. **Data Collection**: Use the provided code or modify it to fetch fresh data using your GitHub API token.
3. **Exploring the Data**: Open `users.csv` and `repositories.csv` to explore the data. You can run additional analysis on these files to gain further insights.

### Key Insights and Findings
This project offers a unique look into the developer community in Stockholm, highlighting popular practices and areas for improvement. The data suggests that while open-source contributions are common, there’s room for growth in repository management, especially in documentation and community engagement.

### Acknowledgments
This analysis was conducted as part of the Data Science curriculum. Special thanks to GitHub for providing API access to the data.

For any questions, feedback, or assistance, mention **Quiz ID: Stockholm:100** on Discourse, or reach out via the contact information provided in the users’ profiles.

