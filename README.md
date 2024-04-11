# Breast_Cancer_Predictor

Breast Cancer Predictor is a web application designed to assist medical professionals in diagnosing breast cancer. It uses a machine learning model to predict whether a breast mass is Benign or Malignant based on cell nucleus measurements provided by the user. This application can serve as a supplementary tool in the medical decision-making process, but it is not a substitute for a professional diagnosis.

# Features

- **User Inputs**: Users can enter cell nucleus measurements using sliders in the sidebar.
- **Radar Chart**: The application visualizes the user inputs as a radar chart, showing different aspects of the measurements.
- **Model Predictions**: The application uses a pre-trained logistic regression model to predict whether the breast mass is benign or malignant. It provides the probability of each prediction.
- **Styling**: Custom CSS styling is applied to the application for a better user experience.

## Installation

To use the Breast Cancer Predictor application:

1. Clone the repository to your local machine:

   git clone https://github.com/your-username/breast-cancer-predictor.git
Navigate to the project directory:

cd breast-cancer-predictor
Install the required Python packages:

pip install -r requirements.txt
Run the application using Streamlit:

streamlit run app.py

# Dependencies

Python 3.7+
pandas
numpy
scikit-learn
streamlit
plotly
pickle5

# Disclaimer
This application is for educational purpose only. It should not be used as a substitute for professional medical diagnosis. Always consult a qualified healthcare professional for medical advice and diagnosis.
