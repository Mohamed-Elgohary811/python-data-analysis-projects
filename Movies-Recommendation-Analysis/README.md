An intelligent **Movie Recommendation System** built using the TMDB 5000 dataset. The system combines **weighted ratings**, **popularity**, and a **hybrid approach** to deliver high-quality personalized movie suggestions.

![Project Banner](Interstellar_photo.jpg)

#### Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Key Insights](#key-insights)
- [Results](#results)
- [How to Run](#how-to-run)
- [Author](#author)

#### Overview

This project analyzes the TMDB 5000 Movies dataset to build multiple recommendation models:
- Simple popularity-based recommendations
- IMDB-style weighted rating system
- Hybrid model combining **rating quality** and **popularity**

The final model recommends movies that are both highly rated **and** popular.

#### Dataset

- **Movies Dataset**: `tmdb_5000_movies.csv` (4803 movies)
- **Credits Dataset**: `tmdb_5000_credits.csv` (cast & crew information)
- **Source**: TMDB (The Movie Database)

#### Features

- Data cleaning and merging
- Exploratory Data Analysis (EDA)
- IMDB Weighted Average Rating calculation
- Popularity-based recommendations
- Hybrid recommendation system (Weighted Rating + Popularity)
- Interactive visualizations using Plotly

#### Technologies Used

- **Python**
- **Pandas** & **NumPy** — Data manipulation
- **Matplotlib** & **Seaborn** — Visualization
- **Plotly** — Interactive charts
- **Scikit-learn** — MinMaxScaler
- **Jupyter Notebook**

#### Methodology

1. **Data Preparation** — Merged movies and credits datasets
2. **Weighted Rating** — Used IMDB formula:  
   `WR = (v / (v + m)) * R + (m / (v + m)) * C`
3. **Popularity Analysis** — Ranked movies by popularity score
4. **Hybrid Model** — Combined normalized weighted rating and popularity (50/50 weight)
5. **Recommendation** — Top movies based on hybrid score

#### Key Insights

- **Interstellar** ranks #1 in the hybrid model due to its excellent balance of high rating and strong popularity.
- **Minions** and **Guardians of the Galaxy** perform very well due to massive popularity.
- Classic high-rated movies like **The Dark Knight**, **The Shawshank Redemption**, and **Fight Club** remain strong recommendations.
- The hybrid approach produces more balanced and realistic recommendations than using rating or popularity alone.

#### Results

**Top Recommended Movies (Hybrid Score):**

1. **Interstellar**
2. **Minions**
3. **Guardians of the Galaxy**
4. **Deadpool**
5. **The Dark Knight**


## 📊 Sample Visualizations

![Weighted Average Ranking](images/weighted_avg.png)
![Popularity Based](images/popularity.png)
![Hybrid Recommendation](images/hybrid_score.png)
