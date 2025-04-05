# END-TO-END-DATA-SCIENCE-PROJECT

COMPANY:CODTECH IT SOLUTIONS

NAME:V PRIYANKA

INTERN ID:CT06WV72

DOMAIN:DATA SCIENCE

DURATION:6 WEEKS

MENTOR:NEELA SANTOSH

#This end-to-end data science project, developed under the CODTECH internship, implements a house price prediction system using the Boston Housing dataset. The workflow spans data collection, preprocessing, model training, and deployment via a Flask API, culminating in a functional web service. A completion certificate will be issued upon internship conclusion.

Data Collection and Preprocessing: The project begins by loading the Boston Housing dataset (HousingData.csv) using Pandas. Missing values are handled by imputing median values for each column, ensuring data integrity. Exploratory steps include checking data info and confirming no null values remain. Features (e.g., CRIM, RM, LSTAT) are separated from the target variable (MEDV, median house price), and the dataset is split into training (80%) and testing (20%) sets using scikit-learn’s train_test_split.

Model Development: A Linear Regression model from scikit-learn is trained on the preprocessed data to predict house prices based on input features. The model is fitted to the training set, leveraging its simplicity and interpretability for this regression task. The trained model is serialized using pickle and saved as model.pkl for deployment.

Deployment: The project employs Flask, enhanced with flask-ngrok for Google Colab compatibility, to create a RESTful API. A /predict endpoint accepts POST requests with JSON input (feature array), loads the saved model, and returns the predicted house price as a JSON response. Error handling ensures robustness, returning meaningful error messages if issues arise. The API is designed to run locally or via Ngrok’s public URL, making it accessible for real-time predictions.

Deliverable: The final deliverable is a deployed Flask API showcasing the model’s functionality. Users can send feature data (e.g., crime rate, rooms) to the /predict endpoint and receive a predicted house price, fulfilling CODTECH’s requirement for a deployed web app. While the code lacks explicit visualizations (e.g., accuracy plots), the API’s predictive output serves as the primary demonstration of functionality.

Tools and Techniques: The project utilizes Python libraries (Pandas, NumPy, scikit-learn) for data handling and modeling, and Flask for deployment. It demonstrates skills in data preprocessing, machine learning

#Output

![Image](https://github.com/user-attachments/assets/a250f55f-c879-4804-b214-c76d110c116b)
