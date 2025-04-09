# Women's Tennis Performance Analysis
## Are You Better Off Focusing on Court Surface, Break Point Conversion Rate, or Your Dominant Hand to Win in Tennis? Insights from Women’s Grand Slam Matches (2018-2022)
This project performs a statistical analysis of women's tennis performance, focusing on the relationship between various factors (such as court surface) and player success. Specifically, the analysis addresses research questions such as:
- Does the type of court surface affect the number of wins per player?
- Are certain players more successful on specific court surfaces?
- How does the surface type correlate with match outcomes?

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Research Questions](#research-questions)
- [Analysis Methods](#analysis-methods)
- [Prerequisites](#requirements)
- [Installation/How to Run](#installationhow-to-run)
- [Repository Structure](#repository-structure)
- [Results](#results)
- [License](#license)

## Introduction
This project uses statistical methods to analyze women's tennis data to explore key research questions in the sport. The goal is to provide insights into factors that may influence performance and guide further research.

## Data
Data sources include official tennis tournament databases and player performance statistics. The analysis uses WTA grand slam matches data from 2018 to 2022, containing detailed match statistics including:
- Player information (rank, handedness)
- Match conditions (surface type)
- Performance metrics (aces, break points, etc.)

## Research Questions

This analysis explores several key questions about women's tennis performance:

1. Is Court Surface associated with Number of Aces per Match?
2. Is Player Rank associated with Break-point Conversion Rate?
3. Is Player Handedness associated with Match Outcome?

## Analysis Methods

The study employs various statistical methods including:
- ANOVA tests
- Chi-square tests of independence
- Post-hoc analyses
- Descriptive statistics and data visualization

## Requirements
To run this project, you'll need:
- R Studio(version 4.x or higher)
- Required packages (listed in requirements.txt)

## Installation/How to Run

### 1. Clone the repository:
```bash
git clone https://github.com/marzafiee/Womens-Tennis-Performance-Analysis.git
cd tennis-performance-analysis
```

### 2. Install required packages:
```r
# Install required R packages
install.packages(c("readr", "descr", "stats", "dplyr", "knitr", "ggplot2"))
```

### 3. Alternative package installation using requirements file:
```bash
pip install -r requirements.txt
```

### 4. Knit the analysis/code script in R Studio:
```r
# Open the R Markdown file in RStudio and click the "Knit" button
# Or use the following command in R console:
rmarkdown::render("WTA_R_Code.Rmd")
```

## Repository Structure

- `WTA_R_Code.Rmd`: R Markdown document with code and documentation
- `requirements.txt`: List of required packages

## Results
Key findings from the analysis include:
- Court surface significantly affects player win rates.
- Certain players show a strong preference for specific surfaces.
- The analysis provides a model for predicting match outcomes based on surface type.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
