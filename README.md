#  Data Analysis Project

This project collects user data from the DummyJSON API, cleans and prepares it, and visualizes key insights.

---

##  Project Overview
This project demonstrates the complete data workflow for analyzing user information:

1. **Data Collection & Exploration**  
   - Fetch user data from the [DummyJSON API](https://dummyjson.com/users).  
   - Handle pagination and combine all pages into a single dataset.  
   - Perform initial exploration:  
     - Check dataset shape and column data types.  
     - Identify null values.  
     - Generate statistical summary for numerical columns.  
     - Generate summary for categorical columns.

2. **Data Cleaning & Preparation**  
   - Handle missing values appropriately.  
   - Standardize formats:  
     - Parse address data from JSON to extract city, country, and state.
     - convert BirthDate from string to datetime 
   - Remove duplicates if necessary.  
   - Prepare dataset for analysis.

3. **Data Analysis & Visualization**  
   - Explore distributions of key attributes (e.g., age, gender).  
   - Perform aggregations to extract insights (e.g., average age by gender).  
   - Investigate relationships between variables (e.g., age vs weight).  
   - Create visualizations to communicate findings. 
  

4. **Exporting Dataset**:  
   - Save the cleaned and prepared dataset to `users1.csv` for future use.

---

##  Installation
Install required packages:

```bash
pip install pandas requests matplotlib seaborn
---

