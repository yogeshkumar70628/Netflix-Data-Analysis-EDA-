# Netflix Data Analysis 📊

## Project Overview
This project performs exploratory data analysis (EDA) on the Netflix Movies and TV Shows dataset to discover insights about content distribution, trends, and patterns on the Netflix platform.

The analysis includes data cleaning, statistical exploration, and visualizations to better understand Netflix's content library.

---

## Dataset

The dataset used in this project is **Netflix Titles Dataset**, which contains information about movies and TV shows available on Netflix.

### Dataset Features

- show_id – Unique ID for each title
- type – Movie or TV Show
- title – Title of the content
- director – Director name
- cast – Cast members
- country – Country of production
- date_added – Date added to Netflix
- release_year – Year of release
- rating – Content rating (PG, TV-MA, etc.)
- duration – Duration of the content
- listed_in – Genre/category
- description – Brief description of the content

---

## Project Workflow

### 1. Data Loading
The dataset is imported using Python libraries and loaded into a Pandas DataFrame.

### 2. Data Cleaning
Data preprocessing steps include:

- Checking for missing values
- Removing duplicate records
- Handling null or inconsistent data
- Preparing data for analysis

---

### 3. Exploratory Data Analysis (EDA)

Statistical metrics calculated include:

- Mean
- Median
- Mode
- Range
- Standard Deviation

These statistics help understand the distribution of the dataset.

Example Results:
- Mean: 8807.0
- Median: 2017
- Mode: 2018
- Range: 1925 – 2021
- Standard Deviation: 8.81

---

### 4. Data Visualization

Visualizations are created to explore patterns such as:

- Distribution of Movies vs TV Shows
- Content release trends over time
- Genre distribution
- Country-wise production
- Content ratings distribution

Visualization tools help make the insights easier to understand.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure
Netflix-Data-Analysis

│
├── netflix_data_analysis.ipynb
├── netflix_titles.csv
└── README.md


---

## Key Insights

Some insights obtained from the analysis include:

- Movies dominate Netflix content compared to TV shows.
- Most Netflix content was released after 2010.
- Certain genres appear significantly more frequently.
- Content production is concentrated in specific countries.

---

## How to Run the Project

1. Clone the repository
git clone https://github.com/yourusername/netflix-data-analysis.git

2. Navigate to the project directory
cd netflix-data-analysis

3. Install required libraries
pip install pandas numpy matplotlib seaborn


4. Open the notebook
jupyter notebook netflix_data_analysis.ipynb


---

## Future Improvements

- Add interactive dashboards
- Perform advanced statistical analysis
- Build a recommendation model
- Create machine learning predictions for content trends

---

## Author

Yogesh Kumar

Data Analysis Project – Netflix Dataset
