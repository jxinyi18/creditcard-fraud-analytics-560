# Fraud Analytics: Credit Card Applications
<b> Project by: </b> Joyce Xinyi Jiang
<br> 
<b> Details: </b> Project 1 / DSO 562 / Fraud Analytics / University of Southern California (USC) / Marshall School of Business / M.S. Business Analytics
<br>
<b> Topics: </b> Supervised Learning, Fraud Detection, Big Data, Feature Selection, Model Building, Data Cleaning, Variables Creation, Reporting
<br> </br>
<b> Documents included: </b>
<ol>
  <li> Data Quality Report (DQR) </li>
  <ol type="a">
  <li> Data Quality Report Codes </li>
  </ol>
  <li> Making Variables Summary and Business Problem Statement </li>
  <ol type="a">
  <li> Making Variables Codes PT1 (broken into two parts to accomodate huge file size (1billion rows) </li>
  <li> Making Variables Codes PT2 </li>
  </ol>
  <li> Feature Selection Report </li>
  <ol type="a">
  <li> Feature Selection Codes </li>
  </ol>
  <li> Model Exploration Report </li>
  <ol type="a">
  <li> Model Exploration Report </li>
  </ol>
  <li> Model Selection and Summary of Project </li>
</ol>


# Data Quality Report (DQR)
<b> Goal </b>: Provide initial glean of data characteristics within dataset provided.
<br>
<b> Skills </b>: Data Wrangling and Data Visualization
<br>
<b> Software & Packages used </b>: Python (Matplotlib, Pandas, Numpy, Datetime) on Google Collab/Jupyter Notebook.
<br> </br>
<img width="552" alt="Screenshot 2023-03-14 at 2 45 19 PM" src="https://user-images.githubusercontent.com/85601510/225147118-af23becb-1fdf-4077-b852-1d47121065c6.png">
<br>
<img width="450" alt="image" src="https://user-images.githubusercontent.com/85601510/225147311-0db63066-43f1-44cb-9d7b-cd08a5345362.png">
<br>

# Making Variables & Variables Summary
<b> Goal </b>: Making variables from original fields to quantify fraud likelihood. Created linking variables from original fields into unique values (for example: name + address, ssn + dob) to further identify individuals. 
<br>
<b> Skills </b>: Building Variables and Identifying Business Problems
<br>
<b> Software & Packages used </b>: Python (Matplotlib, Pandas, Numpy, Datetime, Scipy, Sklearn) on Jupyter Notebook.
<br>

# Feature Selection
<b> Goal </b>: To improve model performance, we select some most relevant features to reduce dimensionality in the model, it also allows for flexible model exploration. The results yielded 20 variables, sorted by its filter score, through a process of filtering, 'wrapping' then selecting through filter scores.
<br>
<b> Skills </b>: Feature Selection, Filter, Wrapper
<br>
<b> Software & Packages used </b>: Python (Matplotlib, Pandas, Numpy, Sklearn, Random Forest, LightBGM) on Jupyter Notebook.
<br> </br>
<img width="449" alt="image" src="https://user-images.githubusercontent.com/85601510/225144483-72b79085-f1bd-42e3-84b9-f77e91e24801.png">
<br>

# Preliminary Model Exploration
<b> Goal </b>: To explore performance of different models through variation in combination of respective parameters values and number of variables, in addtion to contexts like over and underfitting. 7 models, including linear and non-linear models, like boosted trees, random forests, etc are re-ran 5 times each to observe and yield average performance measures.
<br>
<b> Skills </b>: Model Exploration, Model Building, Supervised Learning
<br>
<b> Software & Packages used </b>: Python (Matplotlib, Pandas, Numpy, Sklearn, Logistic Regression, Decision Tree, Random Forest, LightBGM, CatBoost, etc) on Jupyter Notebook.
<br> </br>
![image](https://user-images.githubusercontent.com/85601510/225149422-891207f8-66a8-455b-a4bd-b55c4f695615.png)
<br>
<img width="441" alt="image" src="https://user-images.githubusercontent.com/85601510/225149842-c7280702-303b-4236-9c2d-3756839b521e.png">
<br>

# Model Selection and Summary of Results
<b> Goal </b>: To select a final model which performs best for our business goal. With the selected model, we are able to eliminate ~50% of the fraud in this dataset by declining the top 3% of applicants. 
<br>
<b> Skills </b>: Supervised Learning, Model Selection
<br>
<b> Software & Packages used </b>: Python (Matplotlib, Pandas, Numpy, Sklearn, LightBGM) on Jupyter Notebook.
<br> </br>
<img width="452" alt="image" src="https://user-images.githubusercontent.com/85601510/225151285-547e8535-38d6-4626-9e9a-d3f05da39542.png">
<br>
