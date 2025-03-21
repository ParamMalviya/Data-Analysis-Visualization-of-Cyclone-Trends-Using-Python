# Cyclone Data Analysis & Visualization

## Overview
This project analyzes and visualizes tropical cyclone data from the last three years. It uses Python libraries such as Pandas, Matplotlib, Seaborn, and GeoPandas to explore storm trends, intensity, and geographical impact.

## Features
- **Data Cleaning**: Handles missing values and converts relevant data types.
- **Geospatial Mapping**: Plots cyclone tracks on a world map.
- **Statistical Analysis**: Computes average wind speed, pressure, and storm frequency.
- **Visualizations**:
  - Bar Chart: Storm frequency by year
  - Line Graph: Storm intensity over time
  - Scatter Plot: Wind speed vs pressure
  - Pie Chart: Storm distribution by basin
  - Heatmap: Correlation between storm attributes
  - Histogram & Box Plot: Wind speed distribution

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- GeoPandas
- Geodatasets
- Shapely

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/cyclone-analysis.git
   cd cyclone-analysis
   ```
2. Install dependencies:
   ```sh
   pip install pandas matplotlib seaborn geopandas geodatasets shapely
   ```
3. Run the Jupyter Notebook or Python script.

## Dataset
The dataset used (`ibtracs.last3years.list.v04r01.csv`) contains tropical cyclone records, including wind speed, pressure, and location data.

## How to Use
- Run the script to generate cyclone visualizations and insights.
- Modify parameters or data preprocessing as needed.
- Extend the analysis with additional environmental factors.

## Contributions
Feel free to fork this repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.
