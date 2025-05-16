## Description
The **Sea Level Predictor** is a Python-based project designed to visualize historical sea level data and predict future trends using linear regression. The project generates a scatter plot with two lines of best fit and saves the visualization as a PNG file.

## Key Features
- Reads historical sea level data from a CSV file.
- Creates a scatter plot of observed data.
- Adds two lines of best fit:
  - One based on all available data (1880–2050).
  - One based on data from the year 2000 onward (2000–2050).
- Saves the generated plot as `sea_level_plot.png`.

## Technologies Used
- **Python**: Programming language.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations.
- **scipy**: For performing linear regression.

---

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone git@github.com:IngaMaholwana/Sea-Level-Predictor.git
   cd sea-level-predictor

## run the project
python main.py

## run the unittest
python -m unittest test_module.py

Sea Level Predictor project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/sea-level-predictor
