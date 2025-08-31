## **Introduction :~**
This Streamlit application leverages a machine learning model to predict diabetes risk based on individual medical history and demographic information. By *analyzing factors such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level*, this application assists healthcare professionals in identifying patients at risk of developing diabetes. Furthermore, it empowers researchers to explore the intricate relationships between various factors and the likelihood of diabetes occurrence.

## **Key Technologies and Skills :~**
Python \
Pandas\
Numpy\
Scikit Learn\
Streamlit\
Installation

### **To run this project, you need to install the following packages:~**
```
pip install pandas
pip install numpy
pip install scikit-learn
pip install streamlit
```
### **Usage**

To use this project, follow these steps: \

*Clone the repository:* git clone https://github.com/Divine-reveire/Diabetes-Prediction-Model.git
*Install the required packages:* pip install -r requirements.txt
*Run the Streamlit app:* streamlit run app.py
*Access the app in your browser at* http://localhost:8501

To use this project, follow these steps:

Clone the repository: git clone https://github.com/gopiashokan/Diabetes-Prediction-using-Machine-Learning.git
Install the required packages: pip install -r requirements.txt
Run the Streamlit app: streamlit run app.py
Access the app in your browser at http://localhost:8501
## **Features :~**

### Dataset Source--

The analysis is based on the "Diabetes prediction dataset" dataset sourced from Kaggle. This dataset provides a rich source of information that serves as the foundation for predicting diabetes risk.

### Data Preprocessing with Ordinal Encoder--

Prior to model training, the dataset undergoes a crucial preprocessing step. The ordinal encoder is applied to transform categorical variables into numerical values. This transformation ensures that the machine learning model can effectively interpret and learn from the data.

### Machine Learning Model: Random Forest Algorithm--

1] The heart of this project lies in the utilization of the Random Forest algorithm for diabetes prediction. This powerful ensemble learning technique is well-suited for the task at hand, as it excels in handling complex datasets and making accurate predictions.\
2] The model has been trained on the preprocessed data, using a combination of medical history and demographic metrics as input features.\
3] Impressive Accuracy Score.

The predictive model has demonstrated exceptional performance, boasting an accuracy score of 96.88%. This high level of accuracy ensures reliable and trustworthy predictions, making it a valuable tool for both healthcare professionals and researchers.

### User-Friendly Streamlit Application--

This Streamlit application offers an intuitive and user-friendly interface. Users can effortlessly input their medical and demographic information, including gender, age, hypertension, heart diseases, smoking history, BMI, HbA1c level, and blood glucose level.
After providing these details, the application swiftly processes the information and generates a diabetes risk prediction based on the input data. This enables users to quickly assess their potential risk of developing diabetes.
![streamlit_application](https://github.com/user-attachments/assets/7977db39-d39f-4df5-bb04-449f70bcaa79)


