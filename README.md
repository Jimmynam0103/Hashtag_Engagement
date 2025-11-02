# Analyzing Hashtag Sentiments and Engagement on Social Media  
### Understanding How Emotional Tone(sentiment) Influences Audience Engagement on Social Media 

Purpose: This project aims to investigate how the sentiment expressed in a social media posts influences audience engagement.
By analyzing posts labeled as Positive, Neutral, or Negative, we seek to determine whether sentiment has a measurable impact on interaction metrics such likes and retweets. For simplicity, we combine these metrics into single engagmement variable as our primary response measure. Ultimately, the overarching goal is to provide insights into how emotional tone of a post can inform strategies for improving engagement and optimizing social media content performance.
---

## Project Overview

This project explores the relationship between the emotional tone of social media hashtags and user engagement.  
The main goal is to understand whether positive, neutral, or negative sentiments lead to higher interaction levels through likes and retweets.  
### Data
In this analysis, we use a dataset sourced from [Kaggle](https://www.kaggle.com/code/kaitizhao/analysis-for-social-media-platform), consisting of approximately 700 social media posts labeled with sentiment categories (*Positive*, *Neutral*, *Negative*).  
Each post includes engagement metrics- specifically likes and retweets-which allows us to evaluate how audience interaction varies depending on emotional tone of post.  

We will:  
- Review and clean the dataset to ensure consistency and accuracy.  
- Visualize sentiment distribution and engagement levels using Matplotlib and Seaborn.  
- Conduct statistical tests such as ANOVA and Linear Regression to identify whether engagement significantly differs by sentiment type.  
- Interpret results to highlight trends in emotional tone and its effect on audience interaction.  

The findings from this project aim to provide insights into how emotional tone shapes engagement patterns on social media platforms. 

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

The dataset used in this project was sourced from **[Kaggle – Analysis for Social Media Platform](https://www.kaggle.com/code/kaitizhao/analysis-for-social-media-platform)**.  
It is titled *“Sentiment Analysis: Data Processing, Visualization.”*  
This dataset contains approximately **700 social media posts** collected from multiple platforms and labeled with different emotional sentiments: *Positive*, *Neutral*, and *Negative*.  
Each post also includes engagement metrics such as the number of *likes* and *retweets*, making it suitable for studying how emotional tone influences audience interaction.  


---

## Analysis

Analysis was conducted in Python using Jupyter Notebook.

Follow the steps below to reproduce the results:  

1. **Explore the Data** – Review the dataset to understand the structure and identify the key sentiment categories (Positive, Neutral, Negative).  

2. **Visualize Sentiment Distribution** – Create bar charts to show the frequency of each sentiment and identify which emotional tones appear most often.  

3. **Analyze Engagement Patterns** – Calculate and compare the average number of likes and retweets for each sentiment to see how emotional tone affects audience response.  

4. **Identify Top and Bottom Hashtags** – Rank hashtags based on total engagement (likes + retweets) to highlight the most and least engaging ones.  

5. **Perform Statistical Testing** –  
   - Conduct a **one-way ANOVA** to test whether engagement significantly differs among sentiment categories.  
   - Build a **linear regression model** to determine whether sentiment score predicts engagement levels.  

6. **Interpret the Results** – Summarize findings, noting that positive sentiments generate higher engagement, while acknowledging that other contextual factors also contribute to overall interaction patterns.  

---

## Results  

The analysis showed that **positive sentiments** made up the largest portion of the dataset (42%) and received the highest engagement, averaging **45 likes** and **20 retweets** per post. Neutral (33%) and negative (25%) posts showed lower interaction levels overall.  

Hashtags such as *#excitement*, *#serenity*, and *#gratitude* ranked among the top for total engagement (over 700 interactions), while *#traffic* and *#struggle* were among the least engaging (below 25 interactions).  

A **one-way ANOVA** test confirmed a significant difference in engagement across sentiment categories (**F = 9.41, p = 9.22 × 10⁻⁵**), and a **regression analysis** indicated that sentiment was a meaningful but limited predictor of engagement (**R² = 0.025, p < 0.001**).  

Overall, these results suggest that positive emotional tone leads to higher audience interaction, though other contextual factors such as timing, topic, or audience reach also influence engagement patterns.  

---

## Authors

- Jimmy Nam - [@Jimmynam0103](https://github.com/Jimmynam0103/social_media_hastag.git)
- Edwin Okwor - [@kembaoak]
- Anushka Naidu [@anushkanaidu](https://github.com/anushkanaidu)

---

## License

This project is licensed under the **MIT License** – see the full license [here](https://github.com/Jimmynam0103/Hashtag_Engagement/blob/main/License).

---

## Acknowledgements

### Tools and Libraries Used:  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)  
- [Statsmodels](https://www.statsmodels.org/)  

### Data Source:  
- [Kaggle – Analysis for Social Media Platform](https://www.kaggle.com/code/kaitizhao/analysis-for-social-media-platform)  

### Inspiration and Guidance:  
- **Seattle University – DATA 5100 (Foundations of Data Science)** project framework.  
- Course instructor and peers for their valuable feedback and support throughout the project.  
