# Singapore-Flat-Resale
# Singapore  Resale Flat Prices Prediction

## 📘 INTRODUCTION:
This project aims to develop a machine learning model and create a user-friendly online application to predict accurate resale values for apartments in Singapore. 
Using historical resale transactions data, the model considers factors such as location, apartment type, size, and lease duration to estimate the future resale price.
 	The goal is to assist both buyers and sellers by providing a reliable prediction tool . This tool aims to assist both buyers and sellers in making informed decisions, overcoming challenges in the real estate market by offering actionable insights into property values.

## Domain : 
🏘️ Real Estate

## Data Source: 
https://beta.data.gov.sg/collections/189/view

## 🛠 Technology and Skills Takeaway:
* **Python:** A programming language.
* **pandas:** A Python library for data visualization.
* **numpy:** A core Python package for scientific computing.
* **streamlit:** A Python framework to quickly create and share machine learning and data science web apps.
* **scikit-learn:** A machine learning library for Python.
**Pickle:** Used to save and load Python objects for later use.

## 📚 Packages and Libraries
•	pip install numpy
•	pip install pandas
•	pip install scikit-learn
•	pip install matplotlib
•	pip install seaborn
•	pip install streamlit
•	pip install streamlit_option_menu
•	
## 📘 Overview
### 🔁 Data Collection and Preprocessing
* Data Source : Downloaded historical resale flat data from official HDB sources, covering the period from 1990 to the current date.
* Initial Cleaning: Handled missing values, corrected inconsistencies, and ensured the data's integrity.
* Feature Engineering: Enhanced the dataset by creating new features and transforming existing ones to better capture the underlying patterns.

### 📊 Data Exploration and Handling
* Outlier Detection: Identified and handled outliers to ensure the model's robustness.
* Skewness Correction: Addressed skewed distributions using appropriate transformations.
* Categorical Encoding: Encoded categorical features using techniques like Label Encoding to convert them into numerical formats suitable for machine learning algorithms.

### 🤖 Model Selection and Training
* **Cross-validated Models: ** 
I cross-validated different regression models, such as Linear Regression and Random Forest Regressor.
* **Evaluated Metrics: ** 
I evaluated performance metrics to determine the best model for predicting resale price.
* **Selected Decision Tree Regressor: ** 
I selected the Decision Tree Regressor based on its superior R-squared and Mean Squared Error metrics.
### 💻 Model Deployment
* **Saving the Model: ** I used pickle to save the trained Decision Tree Regressor model for future use.
* **Creating a Dashboard: ** I built an interactive dashboard with Streamlit so users can input details and get predictions on flat resale prices.
* **Deploying the Application: ** I deployed the app on Render for easy access and smooth performance.

### 👨‍🏫 Reference
* [Python Documentation] (https://docs.python.org/3/)
* [pandas Documentation] (https://pandas.pydata.org/docs/)
* [scikit-learn Documentation] (https://scikit-learn.org/0.21/index.html)
* [NumPy Documentation] (https://numpy.org/doc/)
* [Streamlit Documentation] (https://docs.streamlit.io/)


###Resale Price Prediction
To predict the resale price of a Singapore Flats, follow these steps:
1.	Select the "Predictions" option menu.
2.	Fill in the following required information:
o	Street Name
o	Block Number
o	Floor Area (Per Square Meter)
o	Lease Commence Date
o	Storey Range
3.	Click the "PREDICT RESALE PRICE" button.
4.	The app will display the predicted resale price based on the provided information

### 📞 Contact
          EMAIL : boomica3123@gmail.com
