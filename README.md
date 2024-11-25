# 🛣️ **Road Accident Data Analysis**  

## **Task Overview**  
This project focuses on analyzing road accident data to uncover insights into the factors contributing to accidents. The goal is to explore trends in accident severity, weather conditions, and road types to identify patterns and risks associated with different scenarios.  

---

## **Dataset Used**  
- **Source**: Road Accident Dataset  
- **Features**:  
  - **Accident details**: `Accident_Index`, `Accident_Severity`, `Number_of_Casualties`  
  - **Environmental factors**: `Weather_Conditions`, `Road_Surface_Conditions`, `Light_Conditions`  
  - **Location and timing**: `Latitude`, `Longitude`, `Day_of_Week`, `Time`  

---

## **Analysis Done**  

1. **Data Cleaning**  
   - Handled missing values in columns like `Time`, `Road_Surface_Conditions`, and `Carriageway_Hazards`.  
   - Extracted new features like `Hour` from the `Time` column for better trend analysis.  

2. **Exploratory Data Analysis (EDA)**  
   - **Accident Trends**:  
     - Analyzed the distribution of accidents across different hours, days, and months.  
   - **Weather and Light Conditions**:  
     - Explored how adverse weather and low visibility impact accident rates.  
   - **Severity Analysis**:  
     - Examined accident severity by road type and environmental conditions.  
   - **Mapping Hotspots**:  
     - Created visualizations to locate high-accident-density areas.  

3. **Visualization**  
   - Used bar charts, line graphs, and interactive maps to present insights clearly and effectively.  

---

## **Output Insights**  
- **Weather Impact**: Adverse weather conditions such as rain and fog increase accident rates.  
- **Time Trends**: Most accidents occur during evening rush hours, especially on weekdays.  
- **Location Analysis**: Urban areas and highways are hotspots for accidents.  
- **Severity Levels**: Highways tend to have more severe accidents compared to urban roads.  

---

This project highlights key accident patterns and serves as a foundation for further analysis, including predictive modeling and real-time road safety monitoring.
