# Netflix Movies and Tv Shows

## Overview
  This project analyzes the Netflix Movies and TV Shows dataset to uncover insights about its content. It includes details like title, type, director, cast, country, release year, rating, and duration for exploratory data analysis (EDA) and visualization.

## Dataset
- show_id: Unique ID for each title
- type: Movie or TV Show
- title: Name of the movie/TV show
- director: Director(s) of the title
- cast: Main actors/actresses
- country: Country of production
- date_added: Date when the title was added to Netflix
- release_year: Original release year
- rating: Age rating
- duration: Duration of the movie (in minutes) or number of seasons for TV shows
- listed_in: Genre(s)
- description: Brief synopsis of the title

## Project Structure
```
movies_analysis/
│
├── notebooks/
│   └── movies_analysis.ipynb
│ 
├── .gitignore
│
├── README.md
│
└── requirements.txt
```

## Technologies Used
- Python: Data processing and analysis
- Pandas: Data manipulation
- Matplotlib & Seaborn: Data visualization
- NumPy: Numerical computations
- Jupyter Notebook: Interactive analysis

## Installation
1. clone the repository
git clone [repository-url]
cd movies_analysis

2. Create virtual env file
python env -m virtualenv env
env/scripts/activate

3.  Install required packages
pip install numpy pandas matplotlib and seaborn


