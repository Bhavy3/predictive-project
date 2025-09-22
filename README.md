# predictive-project

This is a Python project for Predictive Modelling of Eating-Out Problem using restaurant data from Sydney.

## Features
- Exploratory Data Analysis (EDA) with visualizations
- Regression and classification models (Scikit-Learn, PySpark)
- Geospatial analysis
- Reproducibility with Git, DVC, and Git LFS

## Setup
1. Clone the repository:
	```
	git clone <your_repo_url>
	cd predictive-project
	```
2. Install dependencies:
	```
	pip install -r requirements.txt
	```

## Usage
Open `main.ipynb` in Jupyter Notebook or VS Code and run all cells.

## Data
- `zomato_df_final_data.csv`: Restaurant data
- `sydney.geojson`: Geospatial data

## Reproducibility
- Track data and models with DVC:
  ```
  dvc init
  dvc add zomato_df_final_data.csv sydney.geojson
  dvc remote add -d storage <remote>
  dvc push
  ```

## License
MIT