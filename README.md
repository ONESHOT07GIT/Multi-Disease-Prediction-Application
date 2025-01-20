# Multiple_Disease_Prediction

 ## Multi-Disease Prediction ML Application
 - Tools : Python, Streamlit, Machine Learning Models, Sklearn, Numpy, Pandas , Github 
• Built an interactive web application using Streamlit, enabling real-time prediction of diabetes, heart disease, and kidney
 disease through pre-trained machine learning models stored in Pickle format .
• Enhanced user experience by integrating intuitive dropdown menus, dynamic input fields, and responsive UI, stream
lining medical diagnostics with high prediction accuracy

![Screenshot 2025-01-14 222454](https://github.com/user-attachments/assets/a42f4e89-bad7-4731-a691-e1cf6c3ad688)

The focus is on building multiple disease prediction applications using Python and Streamlit. The  three specific problems related to diabetes, heart disease, and kidney disease. The datasets for these diseases are organized in a folder, and the saved models are available in a pickle format, which will be utilized to create the Streamlit applications. The process begins with setting up a new Python file named app.py and importing necessary libraries, including Streamlit and pickle.

The application interface is designed using Streamlit's sidebar feature, which allows users to select between the three disease prediction models. Each model has its own set of input fields for user data, such as age, glucose levels, and blood pressure for diabetes, and similar relevant metrics for the other diseases. The code includes conditionals to handle user input and invoke the appropriate prediction model based on the selected disease. The user inputs are processed, and predictions are displayed, indicating whether the individual is likely to have the disease.

 Implemented the logic for each disease model, ensuring that all necessary features are accounted for in the predictions. For instance, the diabetes model incorporates additional features such as new BMI calculations, while the heart disease and kidney disease models follow a similar structure without the need for feature engineering. The final application allows users to input their health data and receive predictions regarding their health status, showcasing the practical application of machine learning in healthcare.
