# Adidas US Sales Analysis

## Project Overview
This project analyzes Adidas sales data in the United States from **2020 to 2021**. The analysis focuses on understanding sales performance across different regions, retailers, and product categories to identify key trends and profitability drivers.

## Dataset
The analysis is based on the `Adidas US Sales Datasets.xlsx` file, which contains **9,648 records** of sales transactions.

### Key Data Points:
- **Time Period:** January 2020 - December 2021
- **Total Sales:** ~$899,902,125
- **Total Profit:** ~$332,134,761
- **Unique Products:** 6 Categories (e.g., Men's Street Footwear, Women's Apparel)
- **Retailers:** Foot Locker, Walmart, Sports Direct, West Gear, etc.

## Key Insights
Based on the analysis in `Adidas_Us_Sales.ipynb`:
- **Top Performing Region:** The **West** region generated the highest profit (~$89.6M), followed by the Northeast.
- **Sales Trends:** Significant sales growth was observed in 2021 compared to 2020, with peaks in mid-to-late 2021.
- **Product Performance:** Analysis includes breakdowns of sales by product category and sales method (In-store, Online, Outlet).

## Project Structure
- `Adidas_Us_Sales.ipynb`: Main Jupyter notebook containing detailed data cleaning, exploratory data analysis (EDA), and visualizations.
- `Adidas_Sales_Analysis.ipynb`: Supplementary analysis notebook.
- `Adidas US Sales Datasets.xlsx`: The raw dataset used for analysis.
- `Adidas Sales Analysis.pdf`: A PDF report summarizing the findings.
- `adidas_kpi_summary_q15.csv`: Summary of Key Performance Indicators.

## Getting Started

### Prerequisites
To run the analysis locally, you need Python installed along with the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `openpyxl` (for reading Excel files)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

### Usage
Open the Jupyter notebooks to view the analysis and run the cells:
```bash
jupyter notebook Adidas_Us_Sales.ipynb
```

## License
This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.