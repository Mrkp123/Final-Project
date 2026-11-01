# COVID-19 Data Analysis and Visualization

## Overview

This project demonstrates a basic analysis and visualization of COVID-19 data using **Python, Pandas, and Matplotlib**. It creates a Pandas DataFrame containing sample COVID-19 statistics, displays the dataset, visualizes trends over time, and calculates the maximum values for cases, recoveries, and deaths.

The project is suitable for beginners learning data analysis and data visualization with Python.

## Features

- **DataFrame Creation:** Stores COVID-19 statistics in a structured Pandas DataFrame.
- **Dataset Display:** Prints the COVID-19 dataset in tabular format.
- **Line Chart Visualization:** Displays cases, recoveries, and deaths over time.
- **Data Comparison:** Compares the trends of cases, recoveries, and deaths.
- **Maximum Value Analysis:** Calculates the maximum number of cases, recoveries, and deaths.

## Technologies Used

- **Python** – Programming language.
- **Pandas** – Data manipulation and DataFrame creation.
- **Matplotlib** – Data visualization and line chart plotting.

## Dataset Information

The project uses a small sample dataset containing five monthly records from March 2020 to July 2020.

| Column | Description |
|---|---|
| Date | Month of the recorded data |
| Cases | Number of reported cases |
| Recoveries | Number of recoveries |
| Deaths | Number of deaths |

**Note:** The dataset is sample data for educational purposes and should not be treated as official COVID-19 statistics.

## Installation

1. Install Python on your system.
2. Install the required libraries:

   ```bash
   pip install pandas matplotlib
   ```

3. Clone this repository:

   ```bash
   git clone https://github.com/your-username/COVID-19-Data-Analysis.git
   ```

4. Navigate to the project directory:

   ```bash
   cd COVID-19-Data-Analysis
   ```

## How to Run

Run the Python file:

```bash
python main.py
```

The program will:
1. Create and display the COVID-19 DataFrame.
2. Generate a line chart showing cases, recoveries, and deaths.
3. Display the maximum values for all three categories.

## Visualization

The project generates a line chart with:
- **Cases:** Shows the change in reported cases.
- **Recoveries:** Shows the change in recoveries.
- **Deaths:** Shows the change in deaths.

The chart includes markers, a legend, axis labels, a title, and a grid for easier interpretation.

## Sample Analysis Output

Based on the sample dataset:

| Metric | Maximum Value |
|---|---:|
| Cases | 4,000 |
| Recoveries | 3,200 |
| Deaths | 120 |

## Python Concepts Practiced

- Creating dictionaries and lists.
- Creating Pandas DataFrames.
- Displaying and accessing DataFrame columns.
- Using the `max()` function.
- Creating line plots with Matplotlib.
- Adding chart titles, labels, legends, and grids.
- Basic exploratory data analysis.

## Learning Objectives

- Understand how to organize data using Pandas.
- Learn basic statistical operations on DataFrame columns.
- Visualize multiple data series using line charts.
- Interpret simple trends in time-based data.
- Develop practical experience with Python data analysis libraries.

## Future Improvements

- Import real COVID-19 datasets from CSV files.
- Add user input for selecting data.
- Calculate average and total values.
- Add bar charts and other visualization types.
- Include more countries and regions for comparison.
- Improve date formatting on the chart.

## Author

**Your Name**

## License

This project is intended for educational and learning purposes. You may modify and extend it for your own practice.
