# Movie Industry Trends Analysis

## Overview
This project analyzes trends in the movie industry, focusing on the evolution and dominance of genres over time and their relationship with key attributes such as budget, popularity, and ratings. The study uses a movie metadata dataset sourced from Kaggle and applies various data analysis techniques to identify patterns and correlations.

## Features
- **Genre Evolution Over Time**: Analyzing the trends of different movie genres over the years.
- **Impact of Budget on Popularity**: Examining whether higher budgets result in higher popularity.
- **Movie Ratings Analysis**: Understanding the relationship between movie ratings and genres.
- **Forecasting Future Genre Trends**: Using Holt-Winters Exponential Smoothing to predict future trends.
- **Impact of Streaming Services**: Investigating the effect of streaming services on the traditional movie industry.

## Dataset
- **Source**: Kaggle - [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
- **Size**: 45,466 rows, 24 columns
- **Key Features**: genres, budget, revenue, runtime, popularity, release_date, vote_average

## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, matplotlib, statsmodels
- **Data Processing**: Cleaning and transforming JSON formatted genre data
- **Visualization**: Various plots to illustrate trends and correlations

## Key Insights
- The **Drama** genre has been the most dominant over the years.
- A significant decline in movie releases was observed in **2017**, coinciding with the rise of streaming services.
- A positive correlation between **budget and popularity** exists, but higher budgets do not always guarantee success.
- **Movie ratings are independent of genre**, highlighting the importance of storytelling and quality.
- Forecasting suggests continued dominance of certain genres, but external factors such as streaming services can alter trends.

## Future Work
- Conduct a deeper exploration into the **2017 anomaly** to identify specific causes.
- Expand analysis to include audience reviews and regional data.
- Implement **machine learning models** for genre-based predictions and recommendation systems.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-industry-analysis.git
   cd movie-industry-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib statsmodels
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook finalProject.ipynb
   ```

## Author
**Siyeon Park** - Case Western Reserve University

## References
- [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
- [The Verge - Movie Industry Decline (2017)](https://www.theverge.com/2018/1/3/16844662/movie-theater-attendance-2017-low-netflix-streaming)
- Various academic papers on movie genre analysis

---
Feel free to modify the details and add your GitHub repository link!
