# Laptop Price and Feature Analysis

This project focuses on analyzing laptop data, specifically using the "Cleaned_Laptop_data" dataset sourced from Kaggle. The dataset contains various fields that allow for detailed analysis of laptop specifications, pricing, and reviews. The purpose of this analysis is to understand the key factors influencing laptop prices and the relationship between specifications, ratings, and reviews.

## Dataset Overview

The dataset includes the following fields:

- **brand**: The manufacturer or brand of the laptop.
- **model**: The specific model name or number of the laptop.
- **processor_brand**: The brand of the laptop's processor (e.g., Intel, AMD).
- **processor_name**: The name of the processor.
- **processor_gnrtn**: The generation of the processor.
- **ram_gb**: The size of RAM in GB.
- **ram_type**: The type of RAM (e.g., DDR4).
- **ssd**: The storage capacity of the SSD in GB.
- **hdd**: The storage capacity of the HDD in GB.
- **os**: The operating system installed (e.g., Windows, macOS).
- **os_bit**: Whether the operating system is 32-bit or 64-bit.
- **graphic_card_gb**: The size of the dedicated graphics card in GB.
- **weight**: The weight of the laptop in kilograms.
- **display_size**: The size of the display in inches.
- **warranty**: The warranty period in years.
- **Touchscreen**: Whether the laptop has a touchscreen (True/False).
- **msoffice**: Whether Microsoft Office is pre-installed (True/False).
- **latest_price**: The latest price of the laptop.
- **old_price**: The original price before discounts.
- **discount**: The discount percentage.
- **star_rating**: The rating given by users (out of 5 stars).
- **ratings**: The number of ratings the laptop has received.
- **reviews**: The number of reviews the laptop has.

## Objectives

- **Price Analysis**: Determine the factors influencing laptop pricing such as brand, processor type, RAM size, storage type, etc.
- **Feature Comparison**: Compare different laptop features (e.g., SSD vs. HDD, processor generation, etc.) and their impact on pricing.
- **Rating and Reviews Correlation**: Examine how the laptop's star rating and the number of reviews correlate with its price and other features.
- **Discount and Warranty Impact**: Explore how discounts and warranty periods impact consumer choice and laptop pricing.

## Technologies Used

- Python
  - Pandas: For data manipulation and cleaning.
  - Matplotlib/Seaborn: For data visualization.
  - Scikit-learn: For machine learning models, if any.
  
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/VikramSrinivas369/Laptop_sales_Analysis.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have the dataset "Cleaned_Laptop_data.csv" from Kaggle. Place the file in the `/data` directory of this project.

## Usage

To run the analysis, execute the following command:
```bash
python laptop_analysis.py
