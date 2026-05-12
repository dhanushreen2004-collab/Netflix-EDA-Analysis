# Netflix EDA Analysis using Python

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python.  

Netflix is one of the world’s leading streaming platforms with thousands of movies and TV shows from different countries, genres, and languages. The main aim of this project is to analyze Netflix content and discover meaningful insights related to content distribution, trends, ratings, genres, and country-wise contributions.

The project includes:
- Data Cleaning
- Feature Engineering
- Data Visualization
- Insight Generation

Using various Python libraries, multiple charts and visualizations were created to better understand Netflix’s content trends and audience preferences.

---

# Problem Statement
Netflix contains a huge collection of movies and TV shows, making it difficult to manually understand content patterns and trends.

This project aims to:
- Analyze Netflix content distribution
- Identify top contributing countries
- Study growth trends over the years
- Understand ratings and genres
- Explore audience-related patterns through visualization

The analysis helps in understanding how Netflix expanded globally and how its content evolved over time.

---

# Objectives
The main objectives of this project are:

- Analyze Movies vs TV Shows distribution
- Identify top content-producing countries
- Analyze content release trends over the years
- Study ratings distribution
- Identify popular genres
- Analyze content additions by year and month
- Handle missing and duplicate data
- Perform feature engineering
- Generate meaningful visual insights

---

# Dataset Information
Dataset Used:
`netflix_titles.csv`

The dataset contains information about:
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

# Technologies Used

## Programming Language
- Python

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

---

# Data Cleaning Process

Several preprocessing techniques were applied to clean the dataset.

## Missing Value Handling

### director
Missing values were filled with:
```python
Unknown
```

### cast
Missing values were replaced with:
```python
Not Available
```

### country
Missing values were filled with:
```python
Unknown
```

### rating
Missing ratings were filled using the mode value.

### date_added
- Missing values handled
- Converted into datetime format

### duration
Type-aware filling:
- Movies → `0 min`
- TV Shows → `0 Season`

---

# Feature Engineering

Additional features were created for better analysis.

## Extracted Features
- `year_added`
- `month_added`

## Duration Splitting
The duration column was split into:
- `duration_num`
- `duration_type`

---

# Exploratory Data Analysis

The following analyses were performed:

## 1. Movies vs TV Shows Distribution
Analyzed the percentage of Movies and TV Shows available on Netflix.

### Insight
Netflix contains significantly more Movies than TV Shows.

---

## 2. Content Release Trend
Analyzed how Netflix content increased over the years.

### Insight
Netflix content growth increased rapidly after 2015.

---

## 3. Top Contributing Countries
Identified countries producing the highest Netflix content.

### Insight
United States contributes the highest amount of content followed by India and the United Kingdom.

---

## 4. Ratings Distribution
Analyzed the most common audience ratings.

### Insight
TV-MA is the most common rating on Netflix.

---

## 5. Genre Analysis
Studied the most popular genres available on Netflix.

### Insight
Drama and International Movies dominate the platform.

---

## 6. Content Added by Year
Analyzed yearly content additions.

### Insight
Maximum content was added between 2017 and 2020.

---

## 7. Month-wise Content Addition
Analyzed which months had maximum content additions.

### Insight
January and July show peak content additions.

---

## 8. Top Directors Analysis
Identified directors with frequent Netflix collaborations.

### Insight
Some directors consistently contribute multiple titles to Netflix.

---

## 9. Top Cast Members
Analyzed frequently appearing actors.

### Insight
Indian cinema actors appeared prominently in the dataset.

---

## 10. Country vs Rating Heatmap
Analyzed rating distribution across countries.

### Insight
USA dominates TV-MA and TV-14 content categories.

---

# Key Findings

- Netflix contains approximately 70% Movies and 30% TV Shows.
- United States is the leading content-producing country.
- Content additions increased rapidly after 2015.
- TV-MA is the most common rating.
- Drama-related genres dominate the platform.
- Netflix aggressively expanded content between 2016 and 2020.
- January and July are peak months for content additions.
- Common themes in descriptions include family, love, and relationships.

---

# Conclusion
This project successfully performed Exploratory Data Analysis on Netflix Movies and TV Shows data using Python.

Through:
- Data Cleaning
- Data Preprocessing
- Visualization
- Feature Engineering

valuable insights were generated regarding:
- Content trends
- Genre popularity
- Ratings
- Country-wise contributions
- Netflix growth patterns

The project demonstrates how data analysis can help understand business trends and user preferences.

---

# Future Enhancements

Future improvements can include:

- Building a Recommendation System
- Sentiment Analysis on descriptions
- Interactive Dashboard using Streamlit or Power BI
- Predictive Machine Learning Models
- Advanced Genre Classification

---

# Project Structure

```bash
Netflix-EDA-Analysis/
│
├── netflix_titles.csv
├── netflix_eda.ipynb
├── README.md
└── Netflix_EDA_Presentation.pptx
```

---

# Author

## Dhanushree N

Aspiring Data Analyst  
Skilled in:
- Python
- SQL
- Data Analysis
- Machine Learning
- Power BI

