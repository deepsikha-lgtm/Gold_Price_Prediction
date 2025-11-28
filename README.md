# Gold Price Prediction App

A machine learning web application that predicts the current price of 1 gram of gold in India based on USD/INR exchange rates.

## 🌐 GitHub Repository

**Project URL:** [https://github.com/deepsikha-lgtm/Gold_Price_Prediction](https://github.com/deepsikha-lgtm/Gold_Price_Prediction)


git clone https://github.com/deepsikha-lgtm/Gold_Price_Prediction

~~~
cd gold-price-predictor
~~~

📋 OVERVIEW

This application uses a pre-trained machine learning model to predict gold prices in Indian Rupees (INR) per gram based on the current USD/INR exchange rate. The model is deployed as an interactive web interface using Gradio.

✨ FEATURES

Real-time Prediction: Get instant gold price predictions

Simple Interface: User-friendly web interface

ML-Powered: Uses scikit-learn regression model

Live Deployment: Shareable web application

Accurate Forecasting: Trained on historical gold price data

🛠️ INSTALLATION

Prerequisites

~~~
Python 3.7 or higher

pip (Python package manager)
~~~

Dependencies

Install the required packages:

~~~
pip install gradio scikit-learn numpy
~~~

🚀 USAGE

Running the Application

Clone or download this repository

Ensure you have the model files in the correct path:

~~~
regressor.pkl - Trained ML model

scaler.pkl - Data scaler
~~~

RUN THE APPLICATION:

python app.py

How to Use

The application will launch in your default web browser

Enter the current USD to INR exchange rate in the input field

Click Submit or press Enter

View the predicted price for 1 gram of gold in INR

Example

~~~
Input:

USD/INR: 83.50

Output:

Predicted Gold Price: 6250.75 INR per gram
~~~

📁 PROJECT STRUCTURE

gold-price-predictor/

│

├── app.py                # Main application file

├── regressor.pkl         # Trained ML model

├── scaler.pkl            # Data scaler

├── requirements.txt      # Python dependencies

├── README.md             # Project documentation

└── .gitignore            # Git ignore file

🔧 TECHNICAL DETAILS

Machine Learning Components

Model: Regression model (Random Forest/Linear Regression)

Preprocessing: StandardScaler for feature normalization

Input Feature: USD/INR exchange rate

Output: Gold price in INR per gram

FRAMEWORK

~~~
Gradio: For web interface deployment

Scikit-learn: Machine learning model

NumPy: Numerical computations

Pickle: Model serialization
~~~

🌐 DEPLOYMENT

The application includes shareable deployment:

demo.launch(share=True)  # Creates a public URL

Alternative Deployment Options

Local only:

demo.launch()  # Local access only

Specific port:

demo.launch(server_name="0.0.0.0", server_port=7860)

📊 MODEL INFORMATION

The prediction model is trained on historical data with the following characteristics:

Features: USD/INR exchange rates

Target: Gold prices in INR/gram

Preprocessing: Standard scaling applied

Model: Pre-trained regression model

🤝 CONTRIBUTING

Contributions are welcome! Please feel free to submit pull requests or open issues for:

Model improvements

UI enhancements

Additional features

Bug fixes

Development Setup

Fork the repository

Create a feature branch:

~~~
git checkout -b feature/amazing-feature
~~~

Commit your changes:

~~~
git commit -m 'Add some amazing feature'
~~~

Push to the branch:

~~~
git push origin feature/amazing-feature
~~~

Open a Pull Request

⚠️ LIMITATIONS

Predictions are based on USD/INR rates only

Model accuracy depends on training data quality

Does not account for sudden market fluctuations

Regional taxes and making charges not included

📄 LICENSE

This project is for educational and demonstration purposes.

📞 SUPPORT

For questions or issues:

Check the existing GitHub Issues

Create a new issue with detailed description

Ensure you include error logs and environment details

Note: This application provides predictions for educational purposes and should not be used for actual financial decisions. Always consult professional financial advisors for investment guidance.
