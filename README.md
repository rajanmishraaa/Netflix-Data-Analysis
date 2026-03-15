# Netflix Dataset Analysis

An exploratory data analysis (EDA) project on the Netflix Titles dataset using Python, Pandas, and Matplotlib. This project uncovers trends and patterns in Netflix's content library through data cleaning, exploration, and visualizations.

---

## Project Structure

```
Netflix-Data-Analysis/
│
├── netflix_data_visualisation.ipynb   # Main Jupyter Notebook
├── netflix_titles.csv                 # Dataset (source: Kaggle)
├── README.md
├── LICENSE
│
└── visualizations/
    ├── movies_VS_tv_shows.png
    ├── Percent_of_rating.png
    ├── duration_of_movies.png
    ├── Number_of_movies_per_release_year.png
    ├── top_10_country_with_highest_release.png
    └── Movies_VS_TV_shows_released_over_the_years.png
```

---

## Dataset Overview

- **Source:** [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Total Records:** 8,807
- **Columns:** 12 (show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description)

---

## Analysis Performed

### 1. Data Exploration
- Loaded and previewed the dataset using `df.head()`, `df.info()`, `df.describe()`, and `df.shape`
- Identified missing values across columns (notably in `director`, `cast`, and `country`)

### 2. Data Cleaning
- Handled null values and filtered data by content type
- Extracted numeric duration values from the `duration` column for movie analysis

### 3. Visualizations

| Chart | Description |
|-------|-------------|
| Bar Chart | Number of Movies vs TV Shows on Netflix |
| Pie Chart | Percentage breakdown of content ratings (TV-MA, TV-14, PG-13, etc.) |
| Histogram | Distribution of movie durations (in minutes) |
| Scatter Plot | Number of titles released per year |
| Horizontal Bar Chart | Top 10 countries with the most Netflix content |
| Line Charts | Trend of Movies and TV Shows released over the years (side-by-side) |

---

## Technologies Used

- Python 3.12
- Pandas - data loading, cleaning, and analysis
- Matplotlib - data visualization
- Jupyter Notebook - interactive development environment

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/rajanmishraaa/Netflix-Data-Analysis.git
   cd Netflix-Data-Analysis
   ```

2. Install the required libraries:
   ```bash
   pip install pandas matplotlib
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and place `netflix_titles.csv` in the project folder.

4. Open the notebook:
   ```bash
   jupyter notebook netflix_data_visualisation.ipynb
   ```

---

## Key Insights

- Netflix has significantly more Movies than TV Shows in its library.
- TV-MA is the most common content rating, indicating a heavy lean toward mature content.
- The majority of movies have a duration between 80 and 120 minutes.
- Content additions saw a sharp increase after 2015, peaking around 2019-2020.
- The United States leads by a large margin in content production, followed by India and the UK.

---

## Author

**Rajan Mishra**  
B.Sc. Data Science Student  
[LinkedIn](https://www.linkedin.com/in/rajan-mishra1111/) | [GitHub](https://github.com/rajanmishraaa)
