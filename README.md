# Bank Customer Churn Analysis

## Table of Content
[project Overview](#project-overview)

[Tools](#tools)

[Data Source](#data-source)

[Results and Findings](#result-and-findings)

[Reconmendations](#reconmendetions)

[Dashboard](#dashboard)

### Project Overview

This data analysis is aimed at providing insights into the customer churned status of a bank. Customer churn is described as a  loss of customers when they stops doing business with a company. It is an important decision for businesses to track, as it can have significant financial implications. For example, acquiring new customers can be more expensive than retaining existing ones, so reducing churn can help a company save on marketing and sales costs.
In the aspect of banking, customer churn refers to customers leaving a bank and taking their business elsewhere. This can be a significant issue for banks, as acquiring new customers can be more expensive than retaining existing ones. Therefore, banks may implement strategies to reduce customer churn and retain valuable customers.
There are many factors that can contribute to customer churn in the banking industry, such as dissatisfaction with service, high fees or charges, or a lack of convenient or innovative services. Banks may also face competition from other financial institutions that offer more attractive products or services.
in this project, there is the analysis about why customer churn from bank and how to retain them based on data.

### Tools

This includes some interesting code/features I worked with 

```Dax
Number of Customers = COUNT('Bank Customer Data'[customer ID])

Customers Lost = CALCULATE(COUNT('Bank Customer Data'[Churn Status]),'Bank Customer Data'[Churn Status]="churned")

Churned Rate = 'Bank Customer Data'[Customers Lost]/'Bank Customer Data'[Number of Customers]

```

### Data Source
[Download Here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqazlMR0QyQUU3dVNHS3NibjFsQjZmSE5jWWpaUXxBQ3Jtc0tubnFCUi1MeVRIcW5FRjVvMDMxdWhFaDhvbTVxM2kzSjd1c1ZQLThneU9zbkkwWlF0TllpNFNjMWNlYVFsWUc0Z0VTT2h5by1aYXhPcnpscmM4ZTdMUldwX3JkYy1BWFBERGVVQWR5NDFZT0JmbFZIMA&q=https%3A%2F%2Ftinyurl.com%2Fz4r3mv34&v=HHu0FLM6Fp0)


### Result and Findings

- There is a total number of 10,000 customers, 4543(45.43%) are female and 5457(54.57%) are male.
- The age group of 31-50 carries the highest customer percentage and around 20.4% of the total number of customers are churning.
- The Female gender is churning more than the Male gender
- Likewise it is discovered that the credit card owners has the higher rate of churned more than the not owned
- Germany and France customer are churning the most with 39.96% and 39.76% respectively while spain comes with the lowest rate having 20.27%
- I also discovered that the credit score group between the rate of 501-700 , the not active  customers and the ones with 100,000 to 200,000 account balance has the highest churned and churned rate.
- We can also conclude that Customers with an age range of over 20 years to under 40 tend not to churn. However, from the age of 40, the level of churn starts to increase until around the age of 60.


### Reconmendations

1.Both male and the female gender needs to be innovated to do their business with the bank
2.The not Active ones should be reached out to with attractive insentives as to become an active customer 
3.The credit card owner seems to be the most active customers of the bank, therefore steps should be taken to make other customers get their cards and get active in order for the bank to make more profit.
4.Spain need more reaching out to through adverts or other means to boost the bank business there while Germany and France should be encouraged to stay and continue doing business with the bank.
5.The age gap of 31-60 carries the higher percentage of the total number of customers as well as the most churned , this set of customers need to be paid more attention to
6.Those with high credit balance are good for business and it seems they have the higher churning rate, measures should be taking to prevent the loss of the set of customers.


### Dashboard


![bank customers churned](https://github.com/ADETOLAADEBANJI/Churned-Bank-Data-Analysis/assets/149164492/f5538c81-75ea-4346-84f3-05bfe9217740)
