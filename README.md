# YouTube Data Analysis

## Project Overview
The YouTube Data Analysis project addresses the challenges associated with harnessing insights from the vast and diverse landscape of YouTube data. The project aims to design and implement a robust data management and analysis system using the Kaggle dataset of daily popular YouTube videos across various regions.

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
