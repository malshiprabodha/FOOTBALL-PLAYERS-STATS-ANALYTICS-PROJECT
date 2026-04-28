

# **Football Players Stats Analytics (2024–25)⚽**

This project demonstrates the analysis of football player statistics for the 2024-25 season using **PySpark**, **Python**, and **Pandas**. The goal is to uncover valuable insights about player performance, including rankings, trends, and key metrics like goals and assists.

## **Project Overview**

In this project, I analyzed large datasets of football player stats using **PySpark** for distributed data processing and **Seaborn**, **Matplotlib**, and **Pandas** for visualization and analysis. The key tasks included:

* Loading and exploring the dataset.
* Performing data aggregation and transformation.
* Ranking players based on performance metrics like goals and assists.
* Visualizing the data for insights.

## **Tech Stack**

* **PySpark**: For handling large datasets and distributed data processing.
* **Pandas**: For data manipulation and cleaning.
* **Seaborn** & **Matplotlib**: For data visualization and generating charts.
* **Python**: For implementing the overall analysis pipeline.

## **Data Description**

The dataset contains information about football players from the 2024–25 season. Some key columns include:

* **Player_Name**: Name of the player.
* **Goals**: Number of goals scored.
* **Assists**: Number of assists made.
* **Matches_Played**: Number of matches played by the player.

**Dataset Format**: CSV

## **Getting Started**

To run the project locally, you need to have **PySpark** and **Python** installed. Here’s how you can set up your environment:

### **1. Install Required Libraries**

Make sure you have the necessary Python libraries installed:

```bash
pip install pyspark pandas matplotlib seaborn
```

### **2. Download the Dataset**

Make sure to download the dataset from [Kaggle/your data source link] and place it in the project directory.

### **3. Run the Project**

After setting up the environment, you can run the code by executing the notebook `Football_Stats_Analytics.ipynb`. The notebook includes all steps for data exploration, transformation, analysis, and visualization.

```bash
jupyter notebook Football_Stats_Analytics.ipynb
```

## **Usage**

The project demonstrates how to:

* Load large datasets into PySpark for distributed processing.
* Clean and aggregate the data using PySpark DataFrame operations.
* Visualize player performance trends using Seaborn and Matplotlib.
* Rank players based on key performance indicators.

Key insights and visualizations are provided to show trends such as top goal scorers and the relationship between goals and assists.

