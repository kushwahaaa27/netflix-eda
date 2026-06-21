🎬 Netflix Content EDA

Exploratory Data Analysis on the Netflix Titles dataset using Python, Pandas, and Matplotlib.


📌 Objective

Analyze Netflix's content library to uncover trends in content type, growth over time, country-wise production, genres, ratings, and movie durations.


📂 Dataset


File: netflix_titles.csv
Source: Kaggle — Netflix Movies and TV Shows
Contents: Title, type (Movie/TV Show), director, cast, country, date added, release year, rating, duration, genres



🛠️ Tech Stack

ToolPurposePythonCore languagePandasData loading, cleaning, analysisMatplotlibVisualizationsNumPyNumerical operations


🔍 Analysis Performed


Data Inspection — .head(), .info(), missing values, duplicates
Data Cleaning — Filled nulls in director, cast, country, rating, duration; parsed date_added to datetime
Content Type Distribution — Movies vs TV Shows (bar chart)
Year-wise Content Growth — Titles added per year (line chart)
Top Countries — Top 10 content-producing countries
Ratings Distribution — Most common audience ratings (bar chart)
Genre Analysis — Exploded multi-genre column to find top 10 genres (horizontal bar chart)
Movie Duration — Average runtime + distribution histogram
Movies vs TV Shows Over Time — Grouped trend line showing content strategy shift



📊 Key Insights


Netflix has significantly more Movies than TV Shows, reflecting its original content focus
After 2017, TV Show additions grew sharply — a clear strategic shift toward serialized content
USA is the largest content contributor, followed by India and the UK
Most common ratings are TV-MA and TV-14, indicating a mature audience target
Drama and International Movies dominate the genre landscape
Rapid content growth began around 2015, aligning with Netflix's global expansion
Netflix is evolving from a movie-heavy platform toward a balanced Movies + TV Shows library



📁 Project Structure

netflix-eda/
│
├── netflix_titles.csv       # Dataset
├── netflix-eda.ipynb        # Main analysis notebook
└── README.md


🚀 How to Run

bash# Clone the repo
git clone https://github.com/your-username/netflix-eda.git
cd netflix-eda

# Install dependencies
pip install pandas matplotlib numpy

# Launch the notebook
jupyter notebook netflix-eda.ipynb


👤 Author

Arpit — @kushwahaaa27
