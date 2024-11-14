# Delhi Climate Analysis and Forecasting

This project analyzes daily climate data for Delhi, India, and uses the Facebook Prophet model to forecast future temperatures.

## Project Overview

The project involves the following steps:

1. **Data Loading and Exploration:** Loading the dataset, exploring its structure, and visualizing key features like temperature, humidity, and wind speed over time.
2. **Correlation Analysis:** Examining the relationships between different climate variables using a heatmap.
3. **Time Series Analysis:** Analyzing temperature trends over the years and extracting yearly, monthly, and daily patterns.
4. **Forecasting:** Using the Facebook Prophet model to predict future mean temperatures.
5. **Model Evaluation:** Assessing the forecast accuracy using metrics like RMSE and MAE, and visualizing the forecast against actual data.

## Dependencies

This project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- prophet
- scikit-learn

You can install them using pip:

## Usage

1. **Data:** The project uses two CSV files: 'DailyDelhiClimateTrain.csv' for training and 'DailyDelhiClimateTest.csv' for testing. Make sure these files are in the same directory as the notebook.
2. **Running the Notebook:** Execute the code cells in the Jupyter Notebook sequentially. The notebook is well-commented and provides explanations for each step.

## Results

The project provides insights into Delhi's climate patterns and generates a forecast for future mean temperatures. The forecast accuracy is evaluated using RMSE and MAE, and the results are visualized using interactive plots.

## Future Work

- Explore other forecasting models and compare their performance.
- Incorporate additional climate variables into the analysis.
- Develop an interactive dashboard for visualizing the data and forecast.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements or bug fixes.
