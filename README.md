# Car Details Data Analysis Notebook

## Overview

This notebook provides comprehensive analysis and exploration of a used car dataset containing 10,000 entries and 10 columns, including brand, model, year, engine size, fuel type, transmission, mileage, number of doors, owner count, and price. It enables data inspection, statistical summaries, and data-driven insights for various car attributes.[1]

## Features

- Loads a large car dataset using Pandas.[1]
- Generates descriptive statistics for quantitative attributes like price, mileage, year, and engine size.[1]
- Analyzes categorical attributes such as fuel type, transmission type, and car brand.[1]
- Answers common data science questions, e.g.:
  - Distribution of fuel types across cars.
  - Most common car brands.
  - Price trends for cars manufactured after a certain year.
  - Difference in average mileage for Diesel vs Petrol cars.
  - Average car price by transmission and by brand.
  - Correlation analysis between mileage and price.
  - Top brands with lowest average mileage.[1]

## Requirements

- Python (tested on version 3.x)[1]
- Pandas
- NumPy
- Matplotlib (for visualization if included in the cells)[1]

Install with:
```sh
pip install pandas numpy matplotlib
```

## Usage

1. Download or open the `car_details.ipynb` notebook in Jupyter Notebook or Google Colab.[1]
2. Ensure the car dataset CSV (`carpricedataset.csv`) is available in the same directory or Colab workspace.[1]
3. Run the notebook cells sequentially to:
   - Load and preview the dataset.
   - View summaries and analyses for car attributes.[1]

## Dataset Schema

| Column       | Type     | Description                                      |
|--------------|----------|--------------------------------------------------|
| Brand        | string   | Car's manufacturer name (10 unique values)[1]|
| Model        | string   | Specific model of the car (30 unique values)[1]|
| Year         | int      | Manufacturing year (2000–2023)[1]|
| EngineSize   | float    | Engine size in liters (1.0–5.0)[1]|
| FuelType     | string   | Petrol, Diesel, Hybrid, Electric[1]|
| Transmission | string   | Manual, Automatic, Semi-Automatic[1]|
| Mileage      | int      | Total kilometers driven[1]|
| Doors        | int      | Number of doors (2–5)[1]|
| OwnerCount   | int      | Number of previous owners (1–5)[1]|
| Price        | int      | Price in local currency units[1]|

## Example Insights

- Most common brands include Ford, Audi, Volkswagen, Honda, and Chevrolet.[1]
- Electric fuel type is most frequent, followed by Diesel, Hybrid, and Petrol.[1]
- Highest average car price is linked with Automatic transmissions.[1]
- There is a moderate negative correlation between mileage and price ($$-0.55$$), implying higher mileage cars tend to be less expensive.[1]

## License

Add your preferred licensing information here.

***

This README provides essential context for users and contributors to understand the dataset, notebook purpose, and how to use it.[1]

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/97486039/d586f2d2-f8fd-4b20-8b08-aca6ad4766f3/car_details.ipynb)
