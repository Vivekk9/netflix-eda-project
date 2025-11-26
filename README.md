📘 Netflix Titles Dataset — Exploratory Data Analysis (EDA)

🔍 A complete data exploration project using Python, Pandas, NumPy, and Statistics

This project analyzes the Netflix Movies & TV Shows Dataset to understand:

Content trends

Genre distributions

Rating patterns

Release year behavior

Runtime characteristics

Statistical properties

Probability-based insights

The project is structured to reflect real-world data analysis workflows used by data analysts, ML engineers, and data scientists.

🗂️ Project Structure
Netflix-EDA-Project/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_eda.ipynb
│
├── reports/
│   └── Netflix_EDA_Report.pdf          
│
├── images/
│   └── *.png                           
│
├── README.md
└── requirements.txt

📌 1. Overview

The Netflix dataset contains information about Movies and TV Shows including:

Title

Director / Cast

Country

Release Year

Date Added

Rating

Duration

Genre(s)

This project performs end-to-end EDA using:

Pandas → data cleaning & manipulation

NumPy → numerical operations

Matplotlib/Seaborn → visualizations

Statistics → mean, median, std, IQR, probability

Python → list comprehensions, filtering, logic

📊 2. Objectives

✔ Understand distribution of Movies vs TV Shows
✔ Explore genre patterns
✔ Analyze release year trends
✔ Evaluate runtime characteristics
✔ Compute key descriptive statistics
✔ Detect outliers using IQR
✔ Apply probability concepts to the dataset
✔ Visualize important insights

📁 3. Dataset

Dataset source:
Netflix Movies and TV Shows Dataset from Kaggle

Contains ~8800 rows and 12 columns.

Columns include:

type

title

director

cast

country

date_added

release_year

rating

duration

listed_in (genres)

📈 4. Key Insights from EDA
🎬 Content Type Distribution

Movies: ~70%

TV Shows: ~30%

Netflix catalog is movie-heavy.

🕒 Release Year Insights

Mean release year: ~2015

Median: ~2014–2016

Standard deviation: ~6

IQR: ~6

Outliers: ~719 titles (mostly before 2004)

Insight: Netflix content is predominantly modern.

🎭 Genre Analysis

Top genres (with count) include:

International Movies - 2752

Dramas - 2427

Comedies - 1674

International TV Shows - 1351

Documentaries - 869

Insight: Netflix is heavily invested in international content, with International Movies and International TV Shows being the top genres. Dramas and Comedies dominate traditional entertainment genres, while Documentaries highlight Netflix's strong presence in factual, real-world storytelling. 

⭐ Rating Analysis (Movies)

Most common ratings:

TV-MA

TV-14

R

PG-13

Shows that Netflix leans toward mature content.

⏱️ Runtime Analysis (Movies)

Mean runtime: ~95–100 minutes

Median runtime: ~90–95 minutes

Slight right-skew (due to some very long films)

📐 Outlier Detection (IQR Method)

Using IQR bounds:

Lower bound: ~2004

Upper bound: ~2028

Outliers detected: ~719

Most outliers are older classic films.

🎲 Probability Analysis
Event	and Probability
A title is a TV Show	~0.30
A title is from India	~0.10
A title is rated TV-MA	~0.25–0.30

🧪 5. Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

Markdown

Statistics

🧰 6. How to Run the Project
Step 1: Clone the repository
git clone https://github.com/Vivekk9/netflix-eda-project.git
cd netflix-eda-project

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Open the Notebook
jupyter notebook notebooks/netflix_eda.ipynb


Run cells sequentially for full analysis.

📘 7. Visualizations Included

The notebook includes:

Histogram of release years

Genre frequency bar chart

Movie vs TV Show bar chart

Rating distribution

Runtime distribution

Release year boxplot (outlier visualization)

Images saved in /images/.

📝 8. Conclusions

Netflix content is primarily modern (post-2010).

Movies dominate the platform.

Mature (TV-MA, TV-14) content is highly prevalent.

Genres are diverse, with international movies and dramas leading.

Only ~8% (719) of titles are older classics (outliers).

This dataset demonstrates typical patterns of modern streaming platforms.

🚀 9. Future Improvements

Planned additions:

NLP analysis of title descriptions

Time series analysis on date_added

Correlation heatmaps

Genre clustering

Building a movie recommendation model

Deploying dashboard with Streamlit
