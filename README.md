# Zomato Data Analysis

This project involves an in-depth data analysis of Zomato restaurant data to extract insights about restaurant trends, customer preferences, and pricing. The analysis is performed using Python (primarily in a Jupyter Notebook), leveraging popular data science libraries.

## Project Objectives

The main questions addressed in this analysis are:

1. **Online Delivery vs. Offline Services:**  
   Do a greater number of restaurants provide online delivery as opposed to offline services?

2. **Popular Restaurant Types:**  
   Which types of restaurants are most favored by the general public?

3. **Preferred Price Range for Couples:**  
   What price range is preferred by couples for their dinner at restaurants?

## Data

- The dataset (`Zomato_Data_Analysis.ipynb`) used contains information about restaurants, including:
  - Restaurant name
  - Type (e.g., Cafe, Dining)
  - Online order availability
  - Table booking options
  - Ratings and votes
  - Approximate cost for two people
- The data is processed and visualized to extract meaningful insights.

## Key Findings

- **Dining Restaurants** are preferred by a large number of individuals.
- The majority of restaurants fall into the Dining category.
- Analysis covers average ratings, votes, and price ranges for different types of restaurants.
- Trends in online delivery versus offline service are visualized and compared.

## Analysis Techniques

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Grouping and aggregating data to answer the primary questions
- Visualization of data using libraries such as `matplotlib` and `seaborn`
- Statistical analysis (e.g., z-score for outlier detection in votes)

## How to Use

1. Clone or download the repository.
2. Open the `Zomato_Data_Analysis.ipynb` notebook in Jupyter or Google Colab.
3. Run the notebook cells to reproduce the analysis and view the visualizations.

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
```

## Repository Structure

```
Zomato_Data_Analysis/
│
├── Zomato_Data_Analysis.ipynb   # Main analysis notebook
├── zomato-data.csv #Dataset 
```

## Conclusion

This project provides a comprehensive overview of restaurant trends based on Zomato data, helping understand customer preferences and market trends in the restaurant industry.

---

*Feel free to open an issue or submit a pull request if you have suggestions or improvements!*
