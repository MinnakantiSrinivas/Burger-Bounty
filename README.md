# Burger Bounty Food Truck - Hartford, CT Overview  

This project is designed for **Burger Bounty**, a food truck operation based in **Hartford, Connecticut**, to optimize its location strategy and revenue through data-driven insights. By leveraging local data on sales, pricing, and environmental factors, the project predicts sales for various menu items and provides actionable recommendations for truck placement across Hartford and neighboring towns.  

## Key Features  
### 1. **Hartford-Focused Data Analysis**  
- Analyzes data specific to Hartford, CT, and its surrounding towns, including:  
  - **Downtown Hartford**  
  - **West Hartford**  
  - **East Hartford**  
  - **Glastonbury**  
  - **Manchester**  
  - **New Britain**  
  - **Wethersfield**  
- Considers unique local variables such as events, weather conditions, and weekend activity patterns.  

### 2. **Sales Prediction Models**  
- Utilizes linear regression models to predict sales for popular menu items:  
  - **Bounty Hunter**  
  - **Classic Cheeseburger**  
  - **Spicy Mutiny**  
  - **Nature Bounty**  
  - **BEC**  
  - **Double Veggie**  
- Incorporates Hartford-specific factors such as:  
  - Pricing strategies for each menu item.  
  - Weather data like precipitation and temperature.  
  - Local events in each town.  
  - Weekend vs. weekday dynamics.  

### 3. **Revenue Optimization**  
- Calculates expected revenue by combining predicted sales and planned pricing strategies.  
- Provides recommendations for setting prices and choosing optimal locations to maximize revenue.  

### 4. **Interactive Dashboard**  
Built using **Shiny**, the dashboard offers a user-friendly interface for:  
- Adjusting pricing for menu items.  
- Inputting weather conditions (e.g., precipitation and temperature).  
- Specifying event presence in Hartford and surrounding towns.  
- Predicting sales and revenue for different scenarios.  
- Viewing a ranked list of towns based on projected revenue, helping to determine the best truck placement.  

### 5. **Local Events and Weather Integration**  
- Considers events in key towns to tailor recommendations.  
- Adjusts predictions based on weather forecasts to plan for optimal truck locations.  

## How to Use  
1. **Upload Data**: Ensure the data for visits, prices, and sales is available in Excel format.  
2. **Run the Application**: Launch the Shiny app to interact with the dashboard.  
3. **Input Parameters**: Use the UI to set menu prices, weather conditions, and event presence.  
4. **Review Recommendations**: Get detailed predictions for sales and revenue across Hartford and its neighboring towns.  

## Technical Stack  
- **Programming Language**: R  
- **Libraries**:  
  - `readxl`: Data import from Excel files.  
  - `lm`: Linear regression modeling.  
  - `shiny` and `shinydashboard`: Interactive UI and data visualization.  
- **Data Sources**: Localized sales, pricing, and visit data for Hartford, CT.  

## Live Application  
Explore the **Burger Bounty Food Truck Dashboard** live on ShinyApps.io:  
[**Burger Bounty Dashboard**](https://srinivasminnakanti.shinyapps.io/burgerbounty/)  

This project empowers **Burger Bounty** to thrive in the competitive Hartford, CT food truck scene by making strategic, data-driven decisions for location and pricing.  
