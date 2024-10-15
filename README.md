## Amazon QuickSight Data Analytics Project

This project demonstrates how to use **Amazon QuickSight** for analyzing and visualizing the Netflix catalog dataset by connecting it to AWS services like **S3**.



## Table of Contents
- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Setup Instructions](#setup-instructions)
- [Visualization Examples](#visualization-examples)
- [License](#license)

## Project Overview
The project focuses on building a **dashboard** to visualize key trends from the Netflix catalog dataset using Amazon QuickSight.

## Prerequisites
- AWS Account
- Netflix catalog dataset (provided in the project)
- S3 Bucket for dataset storage
- Amazon QuickSight subscription

## Setup Instructions

### 1. Upload Dataset to S3 Bucket
Upload the Netflix dataset to your S3 bucket:

```bash
aws s3 cp /path/to/dataset.csv s3://your-bucket-name/
```

### 2. Connect Dataset to QuickSight
Sign in to Amazon QuickSight.
Create a new dataset by connecting to the S3 bucket where the dataset is stored.
Create Visualizations

### 3. Use QuickSight to create visualizations such as bar graphs, donut charts, and tables.
Build a dashboard to combine these visualizations.
Publish Dashboard
Save and share the dashboard for easy access and data insights.

### 4. Visualization Examples
Bar Graph: Shows the distribution of genres.
Donut Chart: Displays percentage breakdown of movie categories.
Table: Provides a detailed view of the top-rated movies.

## License
This project is licensed under the MIT License.
