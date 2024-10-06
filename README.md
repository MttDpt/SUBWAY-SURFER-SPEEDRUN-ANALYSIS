# Subway Surfer Speedrun Analysis

## Overview

**Subway Surfer Speedrun Analysis** is a data-driven project focused on uncovering insights and patterns within the Subway Surfers speedrunning community. Using data mining techniques, the project leverages a dataset sourced from Speedrun.com, including over 2,800 records of speedrun attempts across various categories and platforms. The analysis aims to provide valuable insights for game developers, marketers, and the broader gaming community to optimize performance and engagement.

## Table of Contents

1. [Overview](#overview)
2. [Project Description](#project-description)
3. [Dataset](#dataset)
4. [Analysis Approach](#analysis-approach)
   - [Descriptive Analysis](#descriptive-analysis)
   - [Diagnostic Analysis](#diagnostic-analysis)
   - [Predictive Analysis](#predictive-analysis)
   - [Prescriptive Analysis](#prescriptive-analysis)
5. [Key Findings](#key-findings)
6. [Technologies Used](#technologies-used)
7. [How to Run the Project](#how-to-run-the-project)
8. [Contributors](#contributors)

## Project Description

This project explores the Subway Surfers speedrunning community using a comprehensive dataset from Speedrun.com. By analyzing speedrun records, player demographics, platform usage, and completion times, the project seeks to:

- Understand patterns in speedrun times across different categories.
- Identify the most popular platforms for speedrun attempts.
- Analyze the common traits of top performers.
- Provide recommendations for game developers to optimize player engagement and performance.

## Dataset

The dataset includes 2,827 entries and 24 features, containing speedrun times, player information, game category details, and platform usage. It is structured as follows:

- **player_id**: Unique identifier for each player.
- **place**: Rank or position of the speedrun on the leaderboard.
- **speedrun_time**: Time taken to complete the speedrun.
- **platform_name**: Platform used (Android, iOS, Web, etc.).
- **category**: The type of speedrun category (Any%, Coin Collection, etc.).

For more information on the dataset, you can check [Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/subway-surfers/data).

## Analysis Approach

The project is structured into four main types of analysis:

### Descriptive Analysis
This section explores the general distribution of speedrun times, player demographics, and platform usage. Key questions answered:
- What is the distribution of speedrun times across different categories?
- How many players participate in each category?
- What are the most popular platforms for speedruns?

### Diagnostic Analysis
In this section, we aim to understand why certain categories have faster or slower completion times and identify common traits of top performers. The key questions include:
- Why do some categories have faster average completion times?
- What are the characteristics of top performers compared to mid-performers?

### Predictive Analysis
Using predictive models like Linear Regression and Neural Networks, this section attempts to predict speedrun times based on key features, offering insights into which factors most influence performance.

### Prescriptive Analysis
Based on the analysis, this section provides actionable recommendations for game developers and marketers:
- Optimize game performance for dominant platforms (e.g., Android).
- Introduce features tailored to top performers.
- Enhance user engagement by offering personalized in-game rewards and achievements.

## Key Findings

- **Most Popular Platform**: Android is the most popular platform for speedruns, followed by iOS.
- **Speedrun Categories**: The "Coins" category has the shortest average speedrun times, while "Mystery Hurdles" has the longest.
- **Top Performers**: Top performers tend to excel in specific categories, such as "Obtain Item" and show different platform preferences than mid-performers.
- **Player Distribution**: The largest portion of players comes from Brazil, followed by the USA.

## Technologies Used

- **Python**: Main programming language for data analysis.
- **Jupyter Notebook**: For interactive coding and analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For visualizing trends and insights.
- **Scikit-learn**: For building predictive models like Linear Regression and Neural Networks.

## How to Run the Project

To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/MttDpt/subway_surfer_speedrun_analysis.git

# Navigate to the project directory
cd subway_surfer_speedrun_analysis

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook analysis.ipynb
```

## Contributors

- Matteo Del Prato - [email](mailto:m.matteodelprato@gmail.com)   [LinkedIn](https://www.linkedin.com/in/matteodelprato/)
