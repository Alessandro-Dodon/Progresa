# Progresa Policy Analysis  

This group project conducts a comprehensive policy analysis of the Progresa program, focusing on its impact on children's education outcomes. A variety of econometric methods are used to assess the effectiveness of the program.

## Methodology

The analysis progresses through multiple stages, using various econometric techniques to understand the impact of the Progresa program:

**Summary Statistics**: Provides an overview of the key variables and characteristics of the dataset.

**Ordinary Least Squares (OLS)**: A basic regression model to estimate the effect of the program on educational outcomes.

**Logistic Regression**: A model used to analyze binary outcomes, such as school attendance.

**Instrumental Variables (IV)**: Used to address potential endogeneity in the data.

**Difference-in-Differences (DiD)**: A quasi-experimental approach to estimate the causal effect of the program by comparing treated and control groups over time.

## Files

### `Progresa.R`
- R script containing the full analysis, including summary statistics and regression models (OLS, Logistic, IV, and DiD).

### `ProgresaEssay.qmd`
- A Quarto document providing a concise overview of the analysis and key findings. Can be rendered as an HTML file.

### `Progresa.dta`
- The dataset used in the analysis.

## User guide

The Progresa.dta file must be downloaded and placed in the same directory as the scripts since the working directory is set to a relative path. The Progresa.R script is self-contained and will run automatically. If any required packages are missing, simply remove the # at the start of the install.packages() lines in the script to install them. The ProgresaEssay.qmd file can be rendered to an HTML file, and it will work seamlessly as long as R and Quarto are installed.

