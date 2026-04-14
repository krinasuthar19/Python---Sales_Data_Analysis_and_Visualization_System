# Sales Data Analysis and Visualization System

## Overview

This project is a Python-based Sales Data Analysis and Visualization system designed using Object-Oriented Programming principles. It enables users to load, clean, analyze, and visualize sales data efficiently.

The system uses Pandas and NumPy for data manipulation and statistical analysis, while Matplotlib and Seaborn are used to generate meaningful visualizations. It also includes synthetic dataset generation to ensure the project runs independently.

---

## Features

### Data Generation and Loading
- Generates synthetic sales dataset automatically if no file is provided
- Loads CSV dataset with proper date formatting

### Data Exploration
- View dataset head
- Display data types and structure
- Generate descriptive statistics
- Identify missing values

### Data Cleaning
- Handle missing values using mean or median
- Fill categorical values using mode
- Ensure dataset consistency

### Data Manipulation
- Perform mathematical operations on columns
- Create new features such as tax calculation
- Convert Pandas data to NumPy arrays
- Demonstrate indexing, slicing, and element-wise operations

### Search, Sort, and Filter
- Filter data based on conditions
- Sort data by columns
- Search for specific values

### Aggregation and Statistical Analysis
- Group data by categories (e.g., region)
- Calculate sum, mean, count
- Perform statistical analysis (standard deviation, variance, percentiles)

### Pivot Tables
- Generate pivot tables for summarized insights

### Data Visualization
Using Matplotlib:
- Line plot (monthly sales trend)
- Bar plot (sales by region)
- Scatter plot (sales vs profit)
- Histogram (profit distribution)
- Pie chart (product distribution)
- Stack plot (regional sales over time)

Using Seaborn:
- Box plot (sales distribution by product)
- Heatmap (correlation matrix)

### Export Visualization
- Save plots as image files (PNG or other formats)

### Menu-Driven Interface
- Interactive CLI-based navigation system

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OS module

---

## Requirements

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
````

---

## How to Run

1. Save the script as:

```bash
sales_analyzer.py
```

2. Run the program:

```bash
python sales_analyzer.py
```

3. Follow the menu options to perform different operations

---

## Dataset

### Synthetic Dataset

The project automatically generates a dataset named:

```
synthetic_sales_data.csv
```

### Dataset Columns

* Date
* Product
* Region
* Sales
* Profit

---

## Project Structure

```
project_folder/
│
├── sales_analyzer.py
├── synthetic_sales_data.csv
└── README.md
```

---

## Use Cases

* Learning data analysis using Pandas and NumPy
* Practicing data visualization techniques
* Understanding real-world sales analytics workflow
* Academic and portfolio projects

---

## Limitations

* Command-line interface (no GUI)
* Synthetic dataset (not real-world data)
* Requires correct user input format

---

## Future Improvements

* Add GUI using Streamlit or Tkinter
* Integrate real-world datasets
* Add dashboard features
* Export reports in PDF/Excel format

---

## Conclusion

This project demonstrates end-to-end data analysis workflow including data generation, cleaning, transformation, analysis, and visualization. It is suitable for beginners and intermediate learners aiming to build strong fundamentals in data analytics.
