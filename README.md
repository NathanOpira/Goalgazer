# Goalgazer

Goalgazer is a data analysis and machine learning project focused on analyzing football match data and predicting match outcomes. The project includes data preprocessing, exploratory data analysis, and a machine learning model for classification tasks.

## Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, and removes duplicates.
- **Exploratory Data Analysis (EDA)**: Visualizes match outcomes, team appearances, and goal trends over time.
- **Machine Learning**: Implements a Random Forest Classifier to predict match outcomes.
- **Model Persistence**: Saves the trained model using pickle for future use.

## Project Structure

- `data/`: Contains the dataset (`results.csv`).
- `notebooks/`: Includes the Jupyter Notebook (`analysis.ipynb`) for data analysis and modeling.
- `model.pkl`: The saved machine learning model.

## Requirements

See `requirements.txt` for the list of dependencies.

## Usage

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook (`analysis.ipynb`) to explore the analysis and run the model.

## License

This project is licensed under the MIT License.