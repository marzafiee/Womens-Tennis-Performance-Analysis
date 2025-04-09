# Women's Tennis Performance Analysis
## Are You Better Off Focusing on Court Surface, Break Point Conversion Rate, or Your Dominant Hand to Win in Tennis? Insights from Women’s Grand Slam Matches (2018-2022)
This project performs a statistical analysis of women's tennis performance, focusing on the relationship between various factors (such as court surface) and player success. Specifically, the analysis addresses research questions such as:
- Does the type of court surface affect the number of wins per player?
- Are certain players more successful on specific court surfaces?
- How does the surface type correlate with match outcomes?

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [How to Use](#how-to-use)
- [Installation](#installation)
- [License](#license)

## Introduction
This project uses statistical methods to analyze women's tennis data to explore key research questions in the sport. The goal is to provide insights into factors that may influence performance and guide further research.

## Data
The dataset used in this project includes match results from various tournaments, covering information on player names, court surfaces, match outcomes, and more. Data sources include official tennis tournament databases and player performance statistics.

## Analysis
The statistical analysis employs various methods, including:
- Descriptive statistics to summarize player performance.
- Regression models to examine the relationship between surface type and match outcomes.
- Visualization of the results through bar charts, scatter plots, and box plots.

## Results
Key findings from the analysis include:
- Court surface significantly affects player win rates.
- Certain players show a strong preference for specific surfaces.
- The analysis provides a model for predicting match outcomes based on surface type.

## How to Use
To run the analysis and replicate the results, follow these steps:

1. Clone the repository:
git clone [https://github.com/marzafiee/Womens-Tennis-Performance-Analysis.git](https://github.com/marzafiee/Womens-Tennis-Performance-Analysis.git)
cd tennis-performance-analysis

3. Install required packages (Python example):
pip install -r requirements.txt

4. Run the analysis scripts:
source("analysis.R")

## Installation
To run this project, you'll need:
- R (version 4.x or higher)
- Required packages (listed below)

You can install the necessary R packages with the following command:
install.packages(c("ggplot2", "dplyr", "tidyr", "lmtest", "ggpubr"))

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
