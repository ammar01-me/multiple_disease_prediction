[README.md](https://github.com/user-attachments/files/22514026/README.md)
# Disease Prediction Using Machine Learning

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/disease-prediction.git
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit application:
```
streamlit run webapp.py
```
2. The application will open in your default web browser.
3. Use the sidebar menu to navigate to the different disease prediction modules.
4. Fill in the required input fields and click the "Predict" button to get the disease prediction result.

## API

The application uses the machine learning models to predict the following:

- Heart Disease Prediction
- Diabetes Prediction
- Hypertension (BP) Prediction
- Lung Cancer Prediction
- Animal Disease Prediction

The models are loaded from pre-trained pickle files located in the `model_&_scaler` and `animal_enc` directories.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

The application has been tested with various input values and scenarios. However, it is recommended to thoroughly test the application with your own data to ensure accurate predictions.
