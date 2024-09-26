# Zomato Data Analysis and Visualization

## Table of Contents

- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Project Evaluation Metrics](#project-evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project focuses on analyzing and visualizing data from Zomato, a popular restaurant discovery and food delivery service. Through data exploration and visualization techniques, this project aims to provide insights into customer preferences, popular cuisines, and trends in the restaurant industry. The findings will be beneficial for stakeholders, including restaurants, food industry players, and investors.

## Project Objectives

- Perform data exploration and cleaning to prepare the dataset for analysis.
- Visualize various aspects of Zomato's data to identify trends and patterns.
- Create an interactive dashboard using Streamlit for data analysis and visualization.

## Dataset

- Zomato Dataset: [Zomato Data CSV](https://raw.githubusercontent.com/nethajinirmal13/Training-datasets/main/zomato/zomato.csv)
- Country Codes: [Country Code Excel](https://github.com/nethajinirmal13/Training-datasets/blob/main/zomato/Country-Code.xlsx)

## Key Features

1. **Data Engineering**:
   - Added a column for prices in Indian Rupees (INR).
   - Compared Indian currency with other currencies.

2. **Dashboard Development**:
   - Dropdown filter to choose country-specific data.
   - Two charts visualizing metrics such as total sales and popular cuisines.
   - Insights on costliest cuisines in India.
   - City filtering for analyzing:
     - Most popular and expensive cuisines.
     - Rating count based on ratings.
     - Online delivery vs. dine-in options in pie chart format.
   - Comparison between cities in India regarding online delivery, dine-in spending, and living costs.

3. **Dashboard Deployment**:
   - Hosted and deployed the dashboard on a web application server for public access.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Gowthame123/Zomato_Data_Analysis_and_Visualization_project.git
   cd zomato-data-analysis
