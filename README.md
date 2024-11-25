# Percentage Predictor

This project predicts the percentage of a student based on the number of hours studied using a simple linear regression model. It is a basic example of supervised machine learning with only two variables: `Hours Studied` and `Percentage Score`.

## Features

- **Simple Linear Regression:** A model trained to predict a student's score based on their study hours.
- **Visualization:** Data points are plotted on a graph to visualize the relationship between hours studied and scores.
- **Predictive Analysis:** Users can input study hours to get predicted scores.

## Dataset

The dataset consists of two columns:
- `Hours`: Number of hours studied.
- `Scores`: Percentage score achieved.

Sample data:
| Hours | Scores |
|-------|--------|
| 2.5   | 21     |
| 5.1   | 47     |
| 8.5   | 75     |
| 3.5   | 30     |
| 9.2   | 88     |

## Visualization

The relationship between study hours and scores is visualized using a scatter plot. The linear regression model fits a line to this data to predict scores.

## Requirements

- Python 3.x
- Libraries: 
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/percentage-predictor.git
   cd percentage-predictor

