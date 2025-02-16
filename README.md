#  Anime IMDb Rating Analysis

## **Project Overview**
This Jupyter Notebook analyzes anime ratings, popularity, and genre trends using a dataset of the top 2000 anime from MyAnimeList. The goal is to explore patterns in IMDb ratings, identify popular anime, and understand how different genres perform.

## **Dataset Overview**
The dataset consists of:
- **Anime Ratings**: IMDb scores assigned to anime.
- **Popularity Rank**: Ranking based on user interactions.
- **Anime Type**: TV series, movies, OVA, etc.
- **Genres**: Different categories like Shounen, Seinen, and Comedy.
- **Studios**: Anime production studios and their influence.

##  **Objectives**
- Load and explore anime data.
- Analyze rating distribution.
- Identify trends in anime popularity and genres.
- Visualize relationships between score, popularity, and demographic categories.


##  **Key Insights from the Analysis**

### 1️ **Anime Rating Distribution**
- The majority of anime have scores **between 7.5 and 8.0**.
- Few anime achieve scores above **8.5 or close to 9.0**.
- **Boxplot analysis** confirms a median rating of **7.8** with some high-rated outliers.

### 2️ **Popularity Rank Distribution**
- Most anime have **low Popularity Ranks**, forming a right-skewed distribution.
- The highest-ranked anime have around **700 entries** in the top category.

### 3️ **Anime Type Analysis**
- TV series make up the **largest portion** of the dataset.
- A bar chart confirms that **TV is the dominant anime type**.

### 4️ **Genre Breakdown**
- **Shounen** is the most popular genre, making up **56.5%** of the dataset.
- Bar charts indicate genre dominance in the dataset.

### 5️ **Visualizing Relationships**
- **Scatterplot of Score vs. Popularity Rank**: Higher-ranked anime tend to have better scores.
- **Boxplots of Score and Popularity Rank by Demographics**: Certain demographics show higher variation in scores.
- **Scatterplot of Popularity Rank vs. Number of Episodes**: No clear correlation, but interesting patterns emerge.
- **Top 10 Studios by Anime Count**: Bar chart showing the most prolific anime studios.

