# YouTube Data Analysis

## Problem Definition
The YouTube Data Analysis project addresses the challenges associated with harnessing insights from the vast and diverse landscape of YouTube data. The issues encompass the need to handle, organize, and extract meaningful information from the ever-expanding pool of videos, channels, and user interactions. It is essential for a company to perform Data Analysis to predict how well their YouTube video would do, or find ways to deploy more customer-centric marketing strategies by learning how to categorize their videos based on various factors like views, comments, etc.

## Objective
The objective of this project is to harness the wealth of information within the Kaggle dataset, focused on daily popular YouTube videos across various regions. Our aim is to design and implement a robust data management and analysis system, presenting an opportunity to explore patterns, preferences, and variations in video popularity within the YouTube platform, and to gain deeper insights into the dynamics of YouTube trends and audience interactions across diverse geographical locations.

## Dataset
The dataset used for this project is from Kaggle and contains statistical information about daily popular YouTube videos across various locations. [Kaggle YouTube New Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## AWS Services Used
- **AWS S3**: Used for storing the dataset and the transformed data in a scalable and secure manner.
- **AWS IAM**: Managed permissions and access control for different AWS services.
- **AWS Glue**: Used for data integration, transformation, and schema creation.
- **AWS Lambda**: Enabled serverless computation to transform JSON data to Parquet format.
- **AWS Athena**: Allowed querying of data stored in S3 using standard SQL.

## Analysis and Strategic Goals
- **Popular Video Categories**: Analyze the distribution of trending videos across different categories to uncover the most prevalent content genres and their respective engagement levels.
- **Regional Analysis**: Perform region-wise analysis of likes, views, or comments of different categories of videos.
- **Dislike and Engagement Analysis**: Explore relationships between views, likes, dislikes, comments, and the time of publication.
- **Temporal Trends**: Analysis of optimal content publication times, including daily and seasonal patterns.
- **Keyword Analysis**: Identification of frequently used tags and keywords in trending videos.
