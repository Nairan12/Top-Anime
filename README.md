
# Anime IMDb Rating Analysis

## **Project Overview**
This Jupyter Notebook analyzes anime ratings, popularity, and genre trends using a dataset of the top 2000 anime from MyAnimeList. The goal is to explore patterns in IMDb ratings, identify popular anime, and understand how different genres perform.

## **Dataset Overview**
The dataset consists of:
- **Anime Ratings**: IMDb scores assigned to anime.
- **Popularity Rank**: Ranking based on user interactions.
- **Anime Type**: TV series, movies, OVA, etc.
- **Genres**: Different categories like Shounen, Seinen, and Comedy.
- **Studios**: Anime production studios and their influence.

## **Objectives**
- Load and explore anime data.
- Analyze rating distribution.
- Identify trends in anime popularity and genres.
- Visualize relationships between score, popularity, and demographic categories.

## **Key Insights from the Analysis**

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

![image](https://github.com/user-attachments/assets/b0b45118-c407-4c84-9f9f-08b2df4a2ca4)
- The majority of anime have scores between 7.5 and 8.0.
- Most anime have ratings between 7.5 and 7.7, making them the most frequent scores.
- As scores increase, the frequency decreases. Anime with scores above 8.5 are less common.
- Few anime achieve scores close to 9.0, showing that only a small percentage are highly rated.

![image](https://github.com/user-attachments/assets/ee309c99-728d-437a-8635-1995c5c1c9e3)
- Around 700 anime are in the first bar, representing the most popular entries in the dataset.
- Fewer anime are present in the 2000 to 4000 rank range (around 400 entries), and this trend continues.
- The distribution is right-skewed, where most anime have low Popularity Ranks.

![image](https://github.com/user-attachments/assets/fdc624ac-5090-42c0-8fc3-e931159f8293)
- The median score is around 7.8, indicating that half of the anime have a score higher than this value and the other half lower.
- Some outliers exist at the top.

![image](https://github.com/user-attachments/assets/15c0bd82-e291-4843-a1ae-06874356940d)
- The "TV" category is the largest, with over 1000 entries, suggesting that most anime in the dataset are TV series.

![image](https://github.com/user-attachments/assets/827fc32e-2b01-4431-935c-4ed7d7b565a3)
- Josei has the highest median score among all demographics, suggesting that anime targeting adult women tend to have higher ratings overall.
- Anime targeted at children tend to have more consistent scores.

![image](https://github.com/user-attachments/assets/fb111299-f635-4371-b45e-8dba169ce312)
- Shounen dominates in popularity, with a lower median rank and more highly ranked anime.
- Shounen has the most outliers, indicating that there are also low-popularity shows in this demographic.

![image](https://github.com/user-attachments/assets/2bd3e310-4f34-482b-a0f3-3fe6de0bffe2)
![image](https://github.com/user-attachments/assets/ceb7598b-e6ca-4e57-a711-739f22f12054)
- TV anime (blue points) tend to have a much larger number of episodes, with one clear outlier reaching around 1750 episodes. 

