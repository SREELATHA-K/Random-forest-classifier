# Random-forest-classifier
problem statement:
    
    This is a universal bank data.Check weather a person has a personal loan or not. It is a classification problem
    ID = unique Id of each customer                     
Age   = Age of the customer                  
Experience = experience of the customer             
Income   = salary of each customer               
ZIP Code  = unique code of customer              
Family    = Type of family              
CCAvg     = average value             
Education = education of the customer             
Mortgage  =  Mortgage            
Personal Loan = Personal Loan          
Securities Account = Securities Account  
CD Account  =CD Account             
Online   = Online          
CreditCard= CreditCard 

## Import Libraries
import os
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
%matplotlib inline

## import randomforest classifier
