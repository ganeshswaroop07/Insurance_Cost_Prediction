# Insurance_Cost_Prediction

nsurance companies need to accurately predict the cost of health insurance for individuals to set premiums appropriately.
Certainly! Let’s extend the details and add a bit more clarity:

---

## Insurance Premium Prediction

### Project Overview

The Insurance Premium Prediction project aims to leverage machine learning techniques to accurately predict health insurance premiums based on a range of individual factors. This comprehensive project includes detailed documentation, data preprocessing, model building, optimisation, and deployment. The primary tools and frameworks used include Python, Jupyter notebooks, and Streamlit for deployment.

### Detailed Documentation

For a thorough step-by-step walkthrough of the entire project, you can refer to the detailed documentation available on [Medium](https://medium.com/@ganeshswaroop07/insurance-cost-prediction-71d6903cb1a6). This resource provides an in-depth explanation of the methodologies and techniques employed throughout the project, from data acquisition to final deployment.

### Notebooks and Code Files

1. **DSML_Porfolio_Project_Insurance_Costs_Prediction.ipynb**

   - This is the primary notebook where the majority of the work has been conducted. It includes extensive data exploration, preprocessing, feature engineering, and model building. The notebook meticulously documents the steps taken to clean and transform the data, select relevant features, and build various machine learning models.
     During the course of the project.

2. **app.py**
   - This is the deployment script used to launch the machine learning model on Streamlit. The Streamlit app provides an interactive interface for users to input data and receive insurance premium predictions. It’s designed to demonstrate the practical application and usability of the model in a real-world scenario.

### Future Work

Further investigation is required to understand the impact of scaled versus unscaled datasets on the performance of Random Forest models and tree-based algorithms. There may be potential mismatches between transformers used during the training and deployment phases, necessitating a thorough review.

Additionally, Exploratory Data Analysis revealed an intriguing pattern: a significant number of individuals with high BMI (Class I, II, and III obesity) at younger ages were found to have the lowest insurance premiums. Although BMI was derived from the Height and Weight features, and health guidelines highlight the serious health implications of obesity, it remains unclear whether insurance companies factor this into their premium calculations. This aspect was beyond the scope of the current project but presents an opportunity for further exploration.
