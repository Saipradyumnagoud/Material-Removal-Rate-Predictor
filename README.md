# Material-Removal-Rate-Predictor# Material Removal Rate Predictor

## Overview
This project builds a machine learning model to predict the **Material Removal Rate (MRR) (mm³/min)** using a dataset containing various machining parameters. The model is trained using a **Random Forest Regressor**, and users can input machining parameters to get real-time predictions.

## Features
- Loads and preprocesses the dataset
- Splits data into training and testing sets
- Scales feature values for better model performance
- Trains a **Random Forest Regressor**
- Evaluates the model using MAE, MSE, RMSE, and R² Score
- Accepts user input to predict MRR dynamically
- Displays feature importance analysis

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mrr-predictor.git
   cd mrr-predictor
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python mrr_predictor.py
   ```

## Usage
1. The script will prompt you to enter machining parameters.
2. After entering the values, the model will predict the **Material Removal Rate**.
3. The results will be displayed on the console.

## Example Output
```
Enter value for Feature1: 10
Enter value for Feature2: 20
...
Predicted Material Removal Rate: 5.67 mm³/min
```

## Contribution
Feel free to fork this repository, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License.

