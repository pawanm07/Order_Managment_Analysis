## OrderManagment
# Data Analysis ,Processing and Visualization Project

## Overview

This project demonstrates a complete data pipeline that extracts data from CSV files, processes it using SQL and Python, and generates insightful visualizations using matplotlib & Plotly.

## Project Structure

- `main.py`: Main script containing all functions and the main execution block.
- `customers.csv`, `orders.csv`, `orderitems.csv`, `products.csv`: CSV files containing the mock data. (Process the Data in SQL and then Use Python libraries too)
- `top_customers_bar_chart.png`, `revenue_by_category_pie_chart.png`, `sales_trend_line_graph.png`, `orders_vs_spent_scatter_plot.png`: Generated visualizations.
- `top_customers_bar_chart.html`, `revenue_by_category_pie_chart.html`, `sales_trend_line_graph.html`, `orders_vs_spent_scatter_plot.html`: Generated interactive visualizations.

## Setup and Run Instructions

### Datasets

- customers.csv  
- orderitems.csv
- products.csv
- orders.csv
          
### Prerequisites

- Python 3.7+
- pip (Python package installer)
- Jupyter Notebook , VSCode 

### Dependencies

Install the required packages using pip:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install plotly
```

### Running the Project

- Ensure all CSV files are in the same directory as main.py:
- Run the main script:

```bash
python main.py
```
## Conclusion

This project showcases the end-to-end process of extracting, processing, and visualizing data from CSV files. It utilizes both SQL for complex data processing and Python libraries like pandas, matplotlib, and Plotly for data manipulation and visualization.

## Contributing

- Fork the repository.
- Create a new branch for your feature or improvement.
- Commit your changes and push to your fork.
- Create a pull request with a detailed description of your changes.
