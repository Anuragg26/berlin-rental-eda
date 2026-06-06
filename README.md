# Berlin Rental Market - Exploratory Data Analysis

## Project Overview
Exploratory data analysis of Berlin Airbnb weekday listings to uncover
what factors drive rental prices in Berlin.

## Dataset
- **Source:** Kaggle - Airbnb Prices in European Cities
- **File:** berlin_weekdays.csv
- **Size:** 1,284 listings, 20 features

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Findings

1. **Room Type drives price the most**
   - Entire home/apt: €352/night
   - Private room: €176/night
   - Shared room: €144/night

2. **Location is the second biggest factor**
   - Within 2km of city centre: €322/night
   - 10km+ from centre: €194/night

3. **Superhost status has minimal impact**
   - Superhosts charge only €11 more on average

4. **Cleanliness rating has no clear price impact**
   - Price is driven by location and room type instead

5. **Guest satisfaction has no direct price impact**
   - Low rated listings can still charge high prices

## Visualisations
- Price by Room Type
- Price by Superhost Status
- Price by Distance from City Centre
- Price by Cleanliness Rating
- Price by Guest Satisfaction
- Overall Price Distribution

## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib jupyter`
3. Open `Berlin_Rental_EDA.ipynb` in Jupyter Notebook
4. Run all cells
