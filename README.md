# AI-Powered Supermarket Sales Analytics \& Quantity Prediction Project Overview :-



This project analyzes supermarket sales data and uses machine learning to predict product quantity sold. The project also identifies unusual transactions using anomaly detection.



The main purpose is to understand sales patterns, customer behavior, product performance, and factors related to the quantity sold.





## Dataset:



The project uses the public Supermarket Sales dataset:



Kaggle:https : //www.kaggle.com/datasets/aungpyaeap/supermarket-sales



Dataset used in Google Colab : https://raw.githubusercontent.com/selva86/datasets/master/supermarket\_sales.csv



The dataset contains 1,000 supermarket transactions with information such as branch, city, customer type, gender, product line, unit price, quantity, payment method, date, time, and rating.



## Technologies Used :

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SQLite
* Google Collab
* 

## Project Work :



The project includes:



1. Loading and inspecting the supermarket sales dataset.
2. Checking missing values and duplicate records.
3. Cleaning date, time, and numeric data.
4. Creating useful features such as hour, day, month, and day name.
5. Performing exploratory data analysis.
6. Analyzing sales using SQL queries in the notebook.
7. Building a Random Forest Regression model to predict Quantity.
8. Evaluating the model using MAE, RMSE, and R².
9. Checking feature importance.
10. Detecting potential unusual transactions using Isolation Forest.
11. Summarizing the main business findings.



## Machine Learning :



The target variable is :'Quantity'

The model uses information such as:

* Branch
* City
* Customer type
* Gender
* Product line
* Unit price
* Hour
* Day
* Month
* Payment
* Rating



Fields that directly contain or calculate sales totals were excluded from the model to avoid data leakage.

The model used is :'Random Forest Regressor'





## Anomaly Detection



Isolation Forest was used to identify potentially unusual transactions based on:

* Unit price
* Quantity
* Total
* Rating

The detected records are only potential anomalies. They do not automatically mean that a transaction is incorrect or fraudulent.





## Final Results Business Findings :



&#x20;  Highest Sales Branch: C

* Highest Sales Product Line: Food and beverages
* Highest Sales Day: Saturday
* Most Used Payment Method: Ewallet
* Average Customer Rating: 6.97
* Total Sales: 322966.75
* Total Quantity Sold: 5510
* Potential Anomalies: 50



### Model Performance

* MAE: 2.435
* RMSE: 2.89
* R²: -0.071
* 

The R² result shows that the current model did not explain the test-set variation in Quantity very well. The model is used here as an academic machine learning demonstration.



## How to Run the Project Google Collab :

1. Open the '.ipynb' notebook in Google Colab.
2. Run the cells from top to bottom.
3. The notebook downloads the public dataset.
4. Run the data cleaning and analysis cells.
5. Run the SQL analysis cells.
6. Run the machine learning and anomaly detection cells.
7. Review the charts, results, and generated output files.



### Local Jupyter Notebook :

Install the required libraries: bash
pip install -r requirements.txt Then open the notebook and run the cells in order.



## Project Files :

* `AnuragDas\_SupermarketSalesAnalytics.ipynb` - Complete project notebook
* `requirements.txt` - Required Python libraries
* `AnuragDas\_SupermarketProjectReport.docx` - Project report
* `README.md` - Project documentation



## Future Scope:



The project can be improved by using a larger and more recent sales dataset, testing additional machine learning models, adding more customer and seasonal features, and developing an interactive dashboard.



## Created by :

**Anurag Das,**

B.Sc.- Computer Science  
National Institute of Science and Technology-(NIST)  
Berhampur, Odisha.

**Internship:** AICTE | IBM SkillsBuild Data Analytics with AI Internship Program 2026.

Thank You !

