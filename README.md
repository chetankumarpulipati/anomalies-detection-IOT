# Anomalies Analysis

This project is designed to analyze sensor data and detect anomalies using various machine learning models. The analysis includes data preprocessing, model training, prediction, and anomaly detection. The results are visualized using plots, and alerts are sent via email if anomalies are detected.

## Project Structure

- anomalies-analysis.ipynb
- Jupyter Notebook containing the code for data analysis, model training, prediction, and anomaly detection.
- `sensor-data.csv`: CSV file containing the sensor data.
- `images/`: Directory to save the generated plots.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/anomalies-analysis.git
    cd anomalies-analysis
    ```

2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook:
    ```sh
    jupyter notebook anomalies-analysis.ipynb
    ```

## Usage

1. Load the sensor data from `sensor-data.csv`.
2. Preprocess the data and create lagged features.
3. Train various machine learning models (ARIMA, AdaBoost, XGBoost, DNN) on the training data.
4. Predict using the trained models and detect anomalies based on predefined thresholds.
5. Visualize the results and save the plots in the `images/` directory.
6. If anomalies are detected, send an alert email using the 

open_default_mail_app

 function.

## Functions

### 

open_default_mail_app(to, subject, body)



This function opens the default mail application with a pre-filled email.

**Parameters:**
- 

to

 (str): Recipient email address.
- 

subject

 (str): Subject of the email.
- 

body

 (str): Body of the email.

**Example:**
open_default_mail_app("example@example.com", "Alert", "Anomaly detected in sensor data.")



## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- The project uses various machine learning models and libraries such as `scikit-learn`, `xgboost`, `tensorflow`, and `statsmodels`.
- The data visualization is done using `matplotlib`.

## Contact

For any questions or issues, please contact [your-email@example.com](mailto:your-email@example.com).
