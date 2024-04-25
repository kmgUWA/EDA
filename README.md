# Exploratory Data Analysis

## Project Overview

This project demonstrates the process of exploratory data analysis (EDA) using R functions and visualization tools. It is an individual effort project aimed at understanding and analyzing the US Accident Injury dataset, obtained from Data.gov and published by the US Department of Labor. The dataset spans across 15 years (2000 to 2015) and has a total of 202,814 observations, with a file size of 140 MB. However, for this project, we have used a smaller dataset containing 2,000 observations. 

## Data

### Specified Dataset

**US Accident Injury dataset** provided for this project for UWA CITS4009 unit(Computational Data Analysis). 

- **Description:**
  - The dataset contains information about accidents and injuries in the United States spanning 15 years.
  - It includes various attributes such as the location of the accident, body part injured, severity of the injury, and more.

- **Download Links:**
  - [US Accident Injury Dataset (.csv)](https://github.com/kmgUWA/EDA/blob/main/us_data_2000.csv)
  - [Data Dictionary (.csv)](https://github.com/kmgUWA/EDA/blob/main/clean_data_dictionary.csv)


## Project Structure

The project follows a typical structure for exploratory data analysis:

1. **Data Loading and Cleaning:** Loading the dataset, handling missing values, and cleaning the data.
2. **Data Exploration:** Exploring the dataset to understand its structure, distributions, and relationships.
3. **Data Visualization:** Visualizing the data using plots and charts to gain insights.
4. **Conclusion:** Summarizing findings and insights drawn from the analysis.

## Tools and Libraries

- **R:** Programming language used for data analysis and visualization.
- **R Libraries:** 
  - `ggplot2`: For creating visualizations.
  - `dplyr`: For data manipulation.
  - `tidyverse`: Collection of R packages.
  - `plotly`: For creating interactive plots.
  
## Getting Started

Please download [EDA_US_injuries_dataset](https://github.com/kmgUWA/EDA/blob/main/EDA_US_injuries_dataset.html) file from the repository.

OR

To run the analysis, you will need R installed on your system. Clone this repository to your local machine and follow these steps:

1. **Install R:**
   If you haven't already, download and install R from the [official website](https://www.r-project.org/).

2. **Install R Packages:**
   Open R or RStudio and run the following command to install the required packages:
   ```R
   install.packages(c("ggplot2", "dplyr", "tidyverse", "plotly"))

   ```
This command will install the necessary packages ggplot2, dplyr, tidyverse, and plotly.

Run the Analysis:
Once the packages are installed, you can open the [R Markdown file or R script](https://github.com/kmgUWA/EDA/blob/main/EDA_US_injuries_dataset.Rmd) EDA_US_injuries_dataset.Rmd containing the analysis and execute the code.

