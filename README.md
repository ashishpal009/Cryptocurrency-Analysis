# Cryptocurrency Analysis Project

## Overview

This project provides an in-depth analysis of various cryptocurrencies over several years. Using interactive dashboards, key metrics such as price trends, volume, and market capitalization of top cryptocurrencies are analyzed. The goal is to present real-time and historical data to assist traders and investors in making informed decisions.

## Table of Contents

- [Executive Summary](#executive-summary)
- [Problem Statement](#problem-statement)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)
- [Tools and Technologies](#tools-and-technologies)
- [Risks and Challenges](#risks-and-challenges)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Executive Summary

This project focuses on providing an in-depth analysis of major cryptocurrencies like Bitcoin, Ethereum, Binance Coin, Solana, and XRP. Using a comprehensive dashboard, key metrics such as price trends, volume, and market capitalization of these cryptocurrencies are analyzed. The data spans from 2013 to 2021 and provides both real-time and historical insights to help investors and traders make informed decisions.

## Problem Statement

- **Background**: Cryptocurrencies are highly volatile and decentralized, requiring continuous monitoring to understand market trends and price behavior.
- **Objective**: The aim is to develop interactive dashboards to monitor critical cryptocurrency metrics such as final close price, highest close price, average volume, and the performance of cryptocurrencies over different periods.
- **Scope**: The analysis includes major cryptocurrencies like Bitcoin, Ethereum, Binance Coin, Solana, XRP, and others. The focus will be on price comparisons, best/worst performers, and correlation analysis over selected date ranges.

## Data Sources

- **Primary Data**: Historical price data and volume for various cryptocurrencies (Bitcoin, Ethereum, etc.) sourced from Kaggle (2013-2021). The data includes Open, High, Low, Close prices, and transaction volume.
- **Secondary Data**: External data sources providing insights on market trends and demographic information.

## Methodology

1. **Data Integration**:
   - Extract cryptocurrency data from CSV files for each coin and load it into Power BI for visualization.
2. **Dashboard Design**:
   - The dashboard is designed to provide insights on:
     - Final close price
     - Highest and lowest close prices
     - Average daily volume and market capitalization
     - Best and worst performers in the last 30 days and 365 days
     - Price correlation among different cryptocurrencies
3. **Interactivity**:
   - The dashboard allows users to filter data based on date range and cryptocurrency to offer personalized insights for specific analyses.

## Expected Outcomes

- **Interactive Dashboards**: Present real-time and historical insights on cryptocurrency performance.
- **Data-driven Decisions**: Traders and investors can use the dashboards to identify trends, make comparisons, and understand market performance.
- **Comprehensive Analysis**: Simplify complex data through visuals and analysis to help users make strategic trading decisions.

## Tools and Technologies

- **Power BI**: Used for dashboard creation and data visualization.
- **Excel**: Used for data extraction and preprocessing.
- **Python**: (for data analysis and visualization before Power BI integration)
  - Libraries: `pandas`, `matplotlib`, `seaborn`

## Risks and Challenges

- **Integration Challenges**: Difficulties may arise when connecting to diverse data sources.
- **Data Accuracy**: Ensuring data accuracy and consistency across dashboards.
- **User Adoption**: There may be challenges with user adoption and training for stakeholders unfamiliar with Power BI.

## Conclusion

This project provides a robust framework for analyzing cryptocurrency data using interactive dashboards. By focusing on key metrics like price trends, market capitalization, and trading volume, the project will help traders and investors gain valuable insights, leading to better-informed decisions.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cryptocurrency-analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd cryptocurrency-analysis
    ```

3. Install the necessary Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. For Power BI, ensure you have Power BI Desktop installed from [here](https://powerbi.microsoft.com/desktop/).

## Usage

### Python Script Usage:
1. Place your cryptocurrency CSV files (e.g., `bitcoin.csv`, `ethereum.csv`) in the root directory of the project.
2. Run the Python script to preprocess the data and generate visualizations.

```bash
python cryptocurrency_analysis.py
