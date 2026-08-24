# 📊 AL Student Results Data Analysis

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg" alt="Pandas">
  <img src="https://img.shields.io/badge/Sweetviz-EDA%20Profiling-success.svg" alt="Sweetviz">
</p>

## 📖 Overview

This repository contains an exploratory data analysis (EDA) of the **AL Student Results Dataset**. The project focuses on data profiling, uncovering insights, and performing basic dataset statistical analysis using Python and Pandas. An automated profiling report is generated using `sweetviz` to provide an in-depth summary of the data distribution, missing values, and feature characteristics.

## 👤 Author Information

- **Name:** W.A.P Buddhini
- **Student Number:** GAHDSE252F-013

## 🛠️ Technologies & Libraries

- **Python:** The core programming language.
- **Pandas:** Used for robust data manipulation, cleaning, and statistical extraction.
- **Sweetviz:** Utilized for generating an automated, high-density HTML profiling report.
- **Jupyter Notebook:** Serves as the interactive development environment for the analysis.

## 📂 Project Structure

```text
📦 DW-AL-Student-results-analyse
 ┣ 📂 day 3
 ┃ ┣ 📜 data_analysis.ipynb          # Main Jupyter Notebook containing the EDA code
 ┃ ┗ 🖼️ Screenshot 2026-08-24.png    # Preview of the analysis output
 ┗ 📜 README.md                      # Project documentation (this file)
```

## 🚀 Getting Started

### Prerequisites

To run this project locally, ensure you have Python installed along with the required libraries. You can install the dependencies via `pip`:

```bash
pip install pandas sweetviz notebook
```

### Running the Analysis

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/pawani04/DW-AL-Student-results-analyse.git
   ```
2. Navigate to the project directory:
   ```bash
   cd DW-AL-Student-results-analyse
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `day 3/data_analysis.ipynb` and execute the cells to load the dataset and generate the `al_data_report.html` profiling summary.

> **Note:** Ensure you update the `csv_path` variable in the notebook to accurately point to your local dataset location before execution.

## 📈 Advanced Data Filtering & Querying

The latest updates to the analysis notebook include advanced data manipulation techniques to extract specific insights:

- **Data Cleaning:** Automatically drops duplicate rows and null values to ensure dataset integrity.
- **District Rank Analysis:** Extracts numeric ranks and filters top-performing students (e.g., District Rank < 500, District 1st Rank).
- **Top Performers (3 'A's):** Identifies students who achieved 'A' grades in all three primary subjects.
- **Stream & Z-Score Filtering:** Queries high-performing students specifically in the `SCIENCE` stream with a `Z-score > 2.0`.

## 📸 Output Preview

Below is a snapshot demonstrating the output from the basic statistical analysis phase:

![Analysis Preview](day%203/Screenshot%202026-08-24%20110316.png)
