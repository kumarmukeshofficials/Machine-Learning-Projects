# Wafer Fault Detection

  1. Problem Statement:  


   The inputs of various sensors for different wafers have been provided. In electronics, a wafer (also called a slice or substrate) is a thin slice                   of semiconductor used for the fabrication of integrated circuits. The goal is to build a machine learning model which predicts whether a wafer needs 
    to be replaced    or not(i.e., whether it is working or not) based on the inputs from various sensors. There are two classes: +1 and -1. 
          • +1 means that the wafer is in a working condition and it doesn’t need to be replaced.
          • -1 means that the wafer is faulty and it needs to be replaced. 


2. Data Description

  The client will send data in multiple sets of files in batches at a given location. Data will contain Wafer names and 590 columns of different sensor values for     each wafer. The last column will have the "Good/Bad" value for each wafer.
  "Good/Bad" column will have two unique values +1 and -1.  
  "+1" represents Bad wafer.
  "-1" represents Good Wafer. 

# How to Run code 

Follow these steps to run the code.

1. Create a new environment 
        conda create -n wafferDetection python==3.6
        
2. Activate your conda 
        conda activate wafferDetection
        
3. Now do installation of requirements.txt file to get all the pacakges.
        pip install -r requirements.txt
        
4. After succesfully installation of requirements.txt
        run the code by using :- python main.py
        
----------------------------------------------------------------------------------------------------------------------------------------------------------------

# Sentiment Analysis


   
        
