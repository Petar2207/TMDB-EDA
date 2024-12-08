
# TMDB Movies Dataset - Exploratory Data Analysis (EDA)

This project is an exploratory data analysis (EDA) of the TMDB 5000 Movies dataset. It focuses on uncovering trends, relationships, and insights about movies based on various features like budget, revenue, runtime, and genres. The analysis uses Python and visualization libraries to present findings in an intuitive and engaging way.

## Features

- Handles missing values and cleans the dataset to ensure robust analysis.
- Visualizes the relationship between key numerical features like budget, revenue, and runtime.
- Generates correlation heatmaps and scatterplots for deeper insights into data relationships.
- Explores revenue trends across genres using bar charts.
- Leverages the TMDB dataset downloaded from Kaggle.

## Prerequisites

- Python 3.x  
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn
```

## Kaggle API Integration

To use the Kaggle API for downloading the dataset, follow these steps:

1. **Generate Kaggle API Token:**  
   Go to your Kaggle account settings and create a new API token. This will download a file named `kaggle.json`.

2. **Place the `kaggle.json` File:**  
   Move the `kaggle.json` file to the directory `%USERPROFILE%\.kaggle` (Windows).

3. **Download the Dataset:**  
   Use the following command to download the dataset via Kaggle CLI:
   ```bash
   kaggle datasets download -d [dataset-name]
   ```
   Replace `[dataset-name]` with the appropriate dataset identifier.

## Visualizations

Key plots generated in this project include:
- Histograms of numerical columns, such as budget and revenue, highlighting distributions and outliers.
- Pair plots for comparing relationships among multiple numerical features.
- Scatterplots for visualizing budget vs. revenue trends.
- Heatmaps for showing correlations between numerical features.
- Genre-based revenue bar charts.

## License

This project is licensed under the MIT License

## Acknowledgements

- Dataset: [TMDB 5000 Movies Dataset on Kaggle](https://www.kaggle.com/)
- Libraries: Pandas, Matplotlib, Seaborn

