# Netflix Titles Dataset — Exploratory Data Analysis

This project performs an end-to-end exploratory data analysis (EDA) of the Netflix Movies and TV Shows dataset. The goal is to understand content trends, distribution patterns, genres, ratings, release years, runtimes, and statistical characteristics using Python and standard data analysis libraries.

---

## 1. Project Structure
```
Netflix-EDA-Project/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_eda.ipynb
├── reports/
│   └── Netflix_EDA_Report.pdf
├── images/
│   └── plots.png
├── README.md
└── requirements.txt
```

---

## 2. Dataset Overview

The dataset contains ~8800 titles, including movies and TV shows. Key columns include:

- type  
- title  
- director  
- cast  
- country  
- date_added  
- release_year  
- rating  
- duration  
- listed_in (genres)

Dataset source: Kaggle — "Netflix Movies and TV Shows".

---

## 3. Objectives

- Analyze content type distribution  
- Explore genre patterns  
- Study release year behavior  
- Compute descriptive statistics  
- Identify outliers  
- Examine ratings distribution  
- Analyze movie runtimes  
- Perform probability-based analysis  
- Visualize key trends  

---

## 4. Key Findings

### Content Type Distribution
- Movies: ~70%  
- TV Shows: ~30%  

### Genre Distribution  
Top genres:
- International Movies (2752) 
- Dramas (2427) 
- Comedies (1674) 
- International TV Shows (1351)  
- Documentaries (869) 

### Release Year Insights
- Mean release year: ~2014  
- Median: 2017  
- Standard deviation: ~8-9 years  
- IQR: ~6  
- Outliers: ~719 titles (mostly before 2004)  
- Catalog is heavily modern and right-skewed.

### Ratings Analysis (Movies)
Most common ratings:
- TV-MA  
- TV-14  
- R  
- TV-PG 

### Runtime (Movies)
- Mean runtime: ~95–100 minutes  
- Slight right-skew due to long-tail distribution.

### Probability Analysis
- P(title is TV Show): 30.38%  
- P(title is from India): 11.88% 
- P(title is rated TV-MA): 36.41% 

---

## 5. Methods and Tools

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- Statistical analysis (mean, median, std, IQR, percentiles, probability)  

---

## 6. How to Run

### Clone repository
```bash
git clone https://github.com/Vivekk9/netflix-eda-project.git
cd netflix-eda-project
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Open notebook
```bash
jupyter notebook notebooks/netflix_eda.ipynb
```

---

## 7. Visualizations Included

- Release year distribution  
- Genre frequency bar chart  
- Movie vs TV Show bar chart  
- Rating distribution  
- Runtime histogram  
- Release year boxplot  

All exported to the `images/` folder.

---

## 8. Conclusions

- Netflix's catalog is predominantly modern (post-2010).  
- Strong focus on drama, international content, comedies, international tv shows, and documentaries.  
- Mature ratings (TV-MA, TV-14) dominate.  
- Only ~8% of titles qualify as outliers (pre-2004).  
- Platform shows global diversity in genres and regions.  

---

## 9. Future Work

- NLP analysis of descriptions  
- Time-series trends using `date_added`  
- Recommendation model (content-based filtering)  
- Streamlit dashboard for interactive EDA  

---

## 10. Author

**Vivek Kamra**  
Data Science & AI Learner  
