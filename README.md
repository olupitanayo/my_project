# my_project
This is strictly for my project -Privacy-preserving health data via smart device
Project Title: Collect and Publish Health data from smart device in a privacy-preserving manner 
The dataset used for this implementation will be added in the folder for reference purpose 
Brief description of the project: This project explores the concept of incorporating differential privacy in a linear regression model, specifically focusing on the impact of adding noise to data to preserve privacy. 
Installation: To run this notebook, please see details below: Ensure you have Python environment running with version Python 3 upward install Jupyter Notebook to enable you open the file ipynb install Python libraries like Pandas, NumPy, matplotlib, scikit-learn by using pip. PS: Ensure you use pip to install the libraries but ensure that the pip is up to date, please see below: 
pip install --upgrade pip 
pip install pandas 
pip install numpy 
pip install matplotlib
pip install scikit-learn For the machine learning using scikit-learn, i used sklearn.model_selection for splitting the dataset into training and testing sets, sklearn.linear_model for creating and training the linear regression model and sklearn.metrics for the evaluation (mean_squared_error, mean_absolute_error, r2_score) 
The implementation code is divided into 3 different sections: Histogram Distribution of Original and Noise-added Data,Evaluation of Predictive Model Performance with Privacy-Preserving Noise and Analysis of the Privacy-Accuracy Trade-off in Predictive Modeling
