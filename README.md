# High School Scoring System Using TOPSIS and AHP

## Project Overview
This project focuses on developing a **high school scoring system** to support UConn's admissions and outreach strategy. The goal is to prioritize high schools based on various factors, such as **yield rate, academic performance, proximity to the university, college-going rates**, and **financial backgrounds** of students. These scores help guide decision-making on where to allocate resources for admissions efforts, particularly in out-of-state markets.

The project uses data provided by UConn admissions and applies **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** and **AHP (Analytic Hierarchy Process)** for scoring and ranking high schools based on multiple criteria.

## Key Features
- **Exploratory Data Analysis (EDA)** to clean and understand the data.
- **Feature Selection** to choose relevant variables for the high school scoring.
- **Clustering Analysis** to categorize schools based on similar traits.
- **AHP for Weight Calculation** to prioritize factors like yield rate, academic level, and distance.
- **TOPSIS Implementation** to compute the final score for each high school.
- **Visualization and Reporting** for data insights and final recommendations.

## Data Sources
The project involves several datasets related to admissions, student demographics, and high school performance. The key dataset files include:
- `Enrollment Status.csv`
- `Decision Stack.csv`
- `Landscape_Data.csv`
- `Demonstrated Interest.csv`
- `MarketView.xlsx`

## Technical Methods
### 1. Analytic Hierarchy Process (AHP)
AHP is a decision-making framework that helps prioritize various factors. In this project, AHP is used to assign weights to the five key factors:
1. Yield Rate
2. Application Assessment
3. Distance
4. College-going rate
5. Financial Background

The pairwise comparison matrix is constructed, and eigenvector methods are used to compute the factor weights. Consistency is ensured using the **Consistency Ratio (CR)**.



### 2. TOPSIS Method
TOPSIS ranks high schools by evaluating how close each school is to the ideal solution (high academic performance, low yield rate, etc.) and how far it is from the worst alternative. Schools with higher proximity to the ideal solution receive a higher score.

## Project Structure

📦High School Scoring System ┣ 📂data ┃ ┣ 📜Enrollment Status.csv ┃ ┣ 📜Decision Stack.csv ┃ ┗ 📜Landscape_Data.csv ┣ 📂notebooks ┃ ┗ 📜UCONN_GROUP_2.ipynb ┣ 📜README.md ┣ 📜requirements.txt ┗ 📜LICENSE



## Requirements
To run the code and reproduce the results, you need to install the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

How to Use the Code
Clone the repository:


You can install the required libraries using the following command:

```bash
pip install -r requirements.txt

git clone https://github.com/your-username/high-school-scoring-system.git
cd high-school-scoring-system


