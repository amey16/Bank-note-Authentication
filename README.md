# Bank-note-Authentication
Bank note authentication api using flask/dockers/streamlit 

# Description
The project is divided into two parts-                                        
1)ML model implementation:Did some basic visualization using matplotlib and seaborn libraries,then implemented random forest classifier                               
2)Building a api to deploy the model                                                                           
   -**Flask and Flasgger**-used flask and flasgger to make a simple app which can take inputs manually as well as files                                
   -**Dockers** - deployed the model using docker comands by building a simple container                               
   -**Streamlit** - most efficient(modified the flask app code) .Streamlit library was used to create an api (manual values)
   
# Dataset - 
  The dataset has 5 features in total namely **variance,skewness,curtosis,entropy,class** .                       
  The first four features are used to predict the class which has 2 values 0(not authentic) and 1(authentic).                 
  The dataset was originally web scraped but available on kaggle (link - https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data )
  
# Repository structure:
 BankNote_Authentication.csv - main dataset                                               
 flaskapp.py - api implementation using flask ad flasgger libraries                                  
 implementation.ipynb - mail model implementation + data visualization                                     
 streamlit.py - api using the streamlit library                                             
 test1.csv - self made csv file to check if api is running or not
