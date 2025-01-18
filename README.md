# Data_Analysis_of_Airbnb
Performed EDA for Airbnb DataSet and found insights and facts using python visualization library

## Agenda

This project focuses on analyzing Airbnb datasets to uncover insights into:

- Pricing trends across different locations.
- Factors influencing listing prices.
- Occupancy rates and seasonal trends.
- Popular property types and their distribution.

By leveraging this analysis, users can better understand the dynamics of the Airbnb market and make data-driven decisions.

---

## Features

- **Data Exploration**: Summary statistics and data visualizations.
- **Location Insights**: Price trends based on neighborhoods and cities.
- **Property Analysis**: Popular property types and pricing insights.
- **Occupancy Trends**: Analysis of seasonal patterns and booking rates.

---

## Data Cleaning and Derived Features

The raw data required significant cleaning to ensure consistency and accuracy. The following steps were undertaken:

- **Handling Missing Values**: Imputed or removed missing entries to maintain dataset integrity.
- **Feature Engineering**: Derived new features such as:
  - `Price_per_Bedroom`: Calculated as the total price divided by the number of bedrooms.
  - `Booking_Rate`: Derived from the number of bookings relative to availability.
  - `Seasonality`: Categorized dates into seasons for seasonal trend analysis.
  - `Revenue_per_City`: Aggregated revenue based on city-level data.

---

## Insights

- **Pricing Trends**:
  - Listings in urban areas are generally priced higher than rural areas.
  - Properties near popular landmarks show premium pricing.

- **Occupancy Rates**:
  - Peak occupancy rates occur during holiday seasons.
  - Coastal areas exhibit higher occupancy during summer months.

- **Property Types**:
  - Apartments and entire homes are the most common property types.
  - Shared rooms have the lowest average price and occupancy rate.

- **Neighborhood Analysis**:
  - Specific neighborhoods in metropolitan cities have the highest listing density.
  - Average price varies significantly between neighborhoods within the same city.

- **Seasonal Trends**:
  - Revenue spikes during festivals and major events.
  - Off-season discounts are commonly observed in less tourist-heavy areas.

- **Customer Preferences**:
  - Customers prefer properties with high ratings and detailed reviews.
  - Amenities such as Wi-Fi and air conditioning significantly influence booking decisions.

---

## Conclusion

The analysis reveals that Airbnb pricing and occupancy are influenced by a mix of geographic, temporal, and customer preference factors. Hosts can optimize their pricing and offerings by:

- Highlighting unique features and amenities.
- Adjusting prices seasonally to match demand.
- Targeting marketing efforts in high-demand neighborhoods.

This data-driven approach can help both hosts and customers make more informed decisions in the Airbnb ecosystem.

## Library Used:
- Numpy, Pandas, Matplotlib, Seaborn
