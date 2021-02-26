# Credit-Bank-Loan

*** ***ML-Model-Flask-Deployment*** ***  
This is a Data Science project to elaborate Machine Learning Models are deployed on production using Flask API.
(developed by : Python, Flask(on PyCharm))

## Project Structure
This project has four major parts :

1. bank credit model.ipynb - this contains a whole process for project data science: calling, cleaning, Exploratory data analysis, processing, modeling and deployment.
2. model.pkl - This contains code for our Machine Learning model to predict credit loan status absed on trainig data in 'traincredit.csv' file.
3. app.py - This contains Flask APIs that receives details through GUI or API calls, computes the precited value based on our model and returns it.
4. templates - This folder contains the HTML template to allow user to enter Bank Clients details and displays the predicted credit loan status. 

## Running the project

1. Ensure that you are in the project home directory. 
2. Run app.py using below command to start Flask API
```
python app.py
```
This would create a serialized version of our model into a file model.pkl.  
By default, flask will run on port 5000.  

Navigate to URL http://localhost:5000  
You should be able to view the homepage !  
Enter valid numerical values in all 5 input boxes and hit Predict.  
If everything goes well, you should be able to see the predcited credit loan status on the HTML page!  
