# Used_Cars_Analysis
This repository contains the analysis of used car data, focusing on pricing trends, feature importance, and data visualization.
# Used Cars 

This contains a dataset and analysis focused on the pricing and features of used cars. The primary goal is to explore the relationships between various car attributes and their asking prices, including factors such as brand, model, fuel type, transmission, and more.

## Dataset

The dataset, **`used_car_dataset.csv`**, includes information on several used cars listed for sale. It contains the following columns:

- **Brand**: The car's brand name.
- **Model**: The car model.
- **Year**: The year the car was manufactured.
- **Age**: The age of the car (calculated as the difference between the current year and the year of manufacture).
- **kmDriven**: The total kilometers the car has been driven.
- **Transmission**: The type of transmission (Manual or Automatic).
- **Owner**: The number of previous owners of the car.
- **FuelType**: The type of fuel used by the car (e.g., Petrol, Diesel).
- **PostedDate**: The date when the car was listed.
- **AdditionInfo**: Additional details about the car (e.g., condition, special features).
- **AskPrice**: The asking price of the car.

Here’s a sample of the data:
| Brand            | Model         | Year | Age | kmDriven    | Transmission | Owner  | FuelType | PostedDate | AdditionInfo                                                           | AskPrice      |
|------------------|---------------|------|-----|-------------|--------------|--------|----------|------------|------------------------------------------------------------------------|---------------|
| Honda            | City          | 2001 | 23  | 98,000 km   | Manual       | second | Petrol   | Nov-24     | Honda City v teck in mint condition, valid genuine car                  | ₹ 1,95,000    |
| Toyota           | Innova        | 2009 | 15  | 190,000 km  | Manual       | second | Diesel   | Jul-24     | Toyota Innova 2.5 G (Diesel) 7 Seater, 2009, Diesel                     | ₹ 3,75,000    |
| Volkswagen       | VentoTest     | 2010 | 14  | 77,246 km   | Manual       | first  | Diesel   | Nov-24     | Volkswagen Vento 2010-2013 Diesel Breeze, 2010, Diesel                  | ₹ 1,84,999    |

## Analysis

The project involves analyzing the dataset with the following objectives:
- **Price Prediction**: Build predictive models to estimate the asking price of a car based on its attributes (e.g., age, brand, fuel type, km driven, etc.).
- **Exploratory Data Analysis (EDA)**: Understand the distribution of car prices, trends by brand, model, fuel type, and other factors.
- **Feature Importance**: Identify the most significant factors affecting the price of used cars.
- **Visualization**: Use charts and graphs to visualize patterns in the dataset, such as price distribution, brand-wise price comparison, etc.

## Requirements

The following Python libraries are required to run the analysis:
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)
- `matplotlib` (for plotting graphs)
- `seaborn` (for statistical data visualization)
- `scikit-learn` (for machine learning models)

You can install the required libraries using:

```bash
pip install -r requirements.txt
