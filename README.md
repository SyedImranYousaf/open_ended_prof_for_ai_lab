# 📊 R Programming: Exploratory Data Analysis & Web Scraping Project

## 📌 Project Overview
This repository contains two data-focused projects implemented using the **R programming language**:

1. **Exploratory Data Analysis (EDA)** on a built-in R dataset  
2. **Web Scraping** from a static website to extract real-world data  

The purpose of this project is to demonstrate practical skills in:
- Data exploration
- Statistical summarization
- Data visualization
- Web data extraction using R

---

## 🎯 Project Objectives

- To explore and analyze a built-in dataset available in R
- To understand data distribution using summary statistics and visualizations
- To perform web scraping on a static website using R
- To extract, structure, and store large real-world datasets
- To practice clean, reproducible data analysis workflows

---

## 🛠 Tools & Technologies Used

- **R Programming Language**
- **RStudio**
- **Packages Used:**
  - `rvest` – Web scraping
  - `dplyr` – Data manipulation
  - `ggplot2` / Base R – Data visualization
  - `xml2` – HTML parsing (dependency)

---

## 🧪 Task 1: Exploratory Data Analysis (EDA)

### 📌 Dataset Used
- **Dataset Name:** `iris`
- **Source:** Built-in R dataset
- **Description:**  
  The `iris` dataset contains measurements of iris flowers:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (Setosa, Versicolor, Virginica)

### 📊 EDA Performed
- Dataset structure analysis
- Summary statistics (mean, median, quartiles, min, max)
- Visualizations:
  - Histogram
  - Boxplot
  - Scatter plot

### 🌐 Task 2: Web Scraping Using R
Website Selected

Website Name: Worldometers – Population by Country

URL: https://www.worldometers.info/world-population/population-by-country/

Website Type: Static HTML website

Data Scraped

The following information was extracted for more than 200 countries:

  - Country Name

  - Population

  - Yearly Change (%)

  - Net Change

  - Population Density

  - Land Area

  - World Population Share

Web Scraping Process

  - The webpage HTML was read using the rvest package

  - All tables on the webpage were extracted

  - The main population table was identified and converted into a structured data frame

  - The dataset was cleaned and prepared for analysis or export
