# DSND Starbucks Capstone Project
Udacity Data Scientists Nanodegree - Starbucks Capstone Project

- [Overview](#overview)
- [Analysis Findings](#findings)
- [File Descriptions](#file-descriptions)
- [Reference and Acknowledgements](#reference-and-acknowledgements)

## Project Overview <a name="overview"></a>
This is the capstone project for the Udacity Data Scientist NanoDegree program by Udacity in collaboration with Starbucks. 
In this project we work with simulated data that mimics customer behavior on the Starbucks rewards mobile app. 

## Analysis Findings <a name="findings"></a>
Analysis findings are documented in the following meduim [article](https://medium.com/@jnaletil/starbucks-app-offers-analysis-4b974aafaf6d)


## File Description <a name="file-descriptions"></a>
* **data** 
  * **portfolio.json:**
    * id (string) - offer id
    * offer_type (string) - type of offer ie BOGO, discount, informational
    * difficulty (int) - minimum required spend to complete an offer
    * reward (int) - reward given for completing an offer
    * duration (int) - time for offer to be open, in days
    * channels (list of strings)
    

  * **profile.json:**  
    * age (int) - age of the customer
    * became_member_on (int) - date when customer created an app account
    * gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
    * id (str) - customer id
    * income (float) - customer's income
    

  * **transcript.json:** 
    * event (str) - record description (ie transaction, offer received, offer viewed, etc.)
    * person (str) - customer id
    * time (int) - time in hours since start of test. The data begins at time t=0
    * value - (dict of strings) - either an offer id or transaction amount depending on the record
  
    
* **Starbucks_Capstone_notebook.ipynb:** jupyter notebook


## Reference and Acknowledgements
The data used in this project was provided by Udacity