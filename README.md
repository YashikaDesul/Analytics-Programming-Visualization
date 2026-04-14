# 📊 Historical Stock Analysis of Axis Bank (R Programming)

## 📌 Overview

This project analyzes 15-minute interval historical stock data for Axis Bank (year 2025). The goal is to identify trading patterns, especially high-volume activity, to support better decision-making and potential revenue optimization strategies.

The analysis is implemented using **R** and includes data cleaning, transformation, statistical analysis, and visualization.

---

## 📂 Project Structure

* `Data Analysis using R_knitting code.Rmd` → Main R Markdown file (properly formatted for knitting into PDF)
* `Data-Analysis-using-R.Rmd` → Plain R script (runs step-by-step in console, no knitting formatting)
* `AXISBANK_15m.csv` → Dataset used for analysis
* `Data-Analysis-using-R.pdf` → Final knitted output

---

## ⚙️ Key Features

* Data preprocessing and type conversion
* Filtering high-volume trades for 2025
* Creation of dependent and independent variables
* Handling missing and duplicate data
* Feature engineering (trade value, volume scaling)
* Statistical analysis:

  * Mean, Median, Mode, Range
* Visualizations:

  * Scatter plot (Volume vs Closing Price)
  * Bar plot (Average Closing Price by Weekday)
* Correlation analysis (Pearson method)

---

## 🚀 How to Run the Project

### Option 1 — Run `.Rmd` (Recommended)

1. Open `Data-Analysis-using-R.Rmd` in RStudio
2. Ensure `AXISBANK_15m.csv` is in the same folder
3. Click **Knit → PDF**

---

### Option 2 — Run `.R` Script

1. Open `Data-Analysis-using-R.R`
2. Run the code line-by-line in RStudio

---

## ⚠️ Important Note

There are **two versions of the code in this repository**:

* ✅ **R Markdown File (`.Rmd`)**

  * Properly structured using code chunks
  * Used for generating the final PDF report
  * Includes formatted output, tables, and plots

* ⚠️ **Plain R Script (`.R`)**

  * Contains the same logic but **without knitting formatting**
  * Intended only for execution in the R console
  * Will NOT produce a formatted report

---

## 📈 Conclusion

The analysis highlights how trading volume influences stock closing prices. Identifying such patterns can help financial institutions optimize trading strategies and improve revenue generation.

---

## 🧠 Requirements

* R
* RStudio
* Packages:

  * `knitr`

---

## 📬 Author

Group 5
Assignment 2 – Data Analysis using R Programming
