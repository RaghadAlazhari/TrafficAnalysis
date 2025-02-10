# Traffic Analysis Project

## Overview
This project analyzes traffic data using a dataset that contains vehicle counts (cars, bikes, buses, and trucks) along with traffic situation classifications. The dataset is collected using a computer vision model that detects four types of vehicles and categorizes traffic into four levels: Heavy, High, Normal, and Low. The goal is to extract meaningful insights and visualizations to understand traffic patterns.

## Dataset Description
The dataset is a CSV file containing the following columns:
- **Time**: The recorded time in hours.
- **Date**: The recorded date.
- **Day of the Week**: The corresponding day of the week.
- **CarCount**: The number of cars detected.
- **BikeCount**: The number of bikes detected.
- **BusCount**: The number of buses detected.
- **TruckCount**: The number of trucks detected.
- **Total**: The total number of all vehicles detected within a 15-minute duration.
- **Traffic Situation**: The classification of traffic congestion into four categories:
  - 1: Heavy
  - 2: High
  - 3: Normal
  - 4: Low

The dataset is updated every 15 minutes, covering one month of traffic data.

## Tasks & Analysis
The analysis focuses on answering the following questions:

1. **Vehicle Distribution Analysis**
   - What is the distribution of vehicle counts for cars, bikes, buses, and trucks?
   - Use boxplots and histograms to visualize the distribution.

2. **Traffic Situation Distribution**
   - What is the distribution of traffic situations?
   - Use a bar chart or pie chart for visualization.

3. **Variation by Day of the Week**
   - How does the vehicle count vary by day of the week?
   - Extract the day of the week from the Time column and use bar plots or boxplots for comparison.

4. **Car Count vs. Traffic Situation**
   - What is the relationship between car count and traffic situation?
   - Use scatter plots, boxplots, or violin plots to visualize.

5. **Bike Count vs. Traffic Situation**
   - What is the relationship between bike count and traffic situation?
   - Use relevant visualizations.

6. **Bus Count vs. Traffic Situation**
   - What is the relationship between bus count and traffic situation?
   - Use relevant visualizations.

7. **Truck Count vs. Traffic Situation**
   - What is the relationship between truck count and traffic situation?
   - Use relevant visualizations.

8. **Total Vehicle Count and Traffic Situation**
   - How does the total vehicle count vary by traffic situation?
   - Calculate the total count for each traffic situation and compare.

9. **Busiest Hours of the Day**
   - What are the busiest hours of the day for traffic?
   - Analyze total vehicle counts by hour and visualize using a bar chart or heatmap.

## Deliverables
- A well-documented Jupyter Notebook (`.ipynb`) containing:
  - Code for data preprocessing and analysis.
  - Visualizations answering each question.
  - Insights derived from the data.

## Requirements
To run the analysis, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn plotly
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/RaghadAlazhari/traffic-analysis.git
   cd traffic-analysis
   ```
2. Run the Jupyter Notebook to explore the analysis.

## License
This project is open-source and available under the [MIT License](LICENSE).

---
For more details, visit my GitHub profile: [RaghadAlazhari](https://github.com/RaghadAlazhari)

