# DSND Starbucks Capstone Project
Udacity Data Scientists Nanodegree - Starbucks Capstone Project

- [Overview](#overview)
- [Project Motivation](#motivation)
- [Analysis Findings](#findings)
- [File Descriptions](#file-descriptions)
- [Reference and Acknowledgements](#reference-and-acknowledgements)

## Project Overview <a name="overview"></a>
This is the capstone project for the Udacity Data Scientist NanoDegree program by Udacity in collaboration with Starbucks. 

## Project Motivation <a name="motivation"></a>
Sending offers to customer is a good strategy to attract new customers and retain existing one. However, not all customers respond in a similar way and individual customers have their own preferences towards received offer types. A customer might be interested in saving money with discounts, another might be more interested in getting more items for less while a different customer would prefer to only know about what is new without caring for any savings. This brings us to the topic of this article and we starting with our problem statement:
We aim to identify Starbucks customers behavior in regards to sent offers. This include analyzing and grouping Starbucks customers to provide customized offers that has higher chance of attracting and retaining customers and influencing their purchases.

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