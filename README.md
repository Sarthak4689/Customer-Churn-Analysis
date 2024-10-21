# Customer-Churn-Analysis-
Nowadays, churn analysis becomes companies’ first priority, because it helps businesses understand why customers are no longer using their products or services. By identifying the factors related to customer leaving, companies can develop targeted strategies to address these issues. For this customer churn analysis, I used free datasets provided by IBM to determine where companies can invest more to reduce customer churn rates.

# Data Overview:-
Telco customer churn: This sample data module tracks a fictional telco company's customer churn based on a variety of possible factors. The churn column indicates whether or not the customer left within the last month. Other columns include gender, dependents, monthly charges, and many with information about the types of services each customer has. 
Source: IBM. 
Location: Team content > Samples > Data. 

The Telco customer churn data module is composed of 5 uploaded files:
 Telco_customer_churn_demographics.xlsx
 Telco_customer_churn_location.xlsx
 Telco_customer_churn_population.xlsx
 Telco_customer_churn_services.xlsx
 Telco_customer_churn_status.xlsx

# Data Modeling:
A star schema model is built for a faster-analyzing process. The Telco Customer Churn Star Schema Model contains:

One fact table:
 Telco_Churn_Fact

Four dimensions tables:
 Services_Dim
 Demographics_Dim
 Location_Dim which contains sub-dimension Population_Dim
 Status_Dim


# Power BI Dashboard:
The dashboard consists of multiple pages, and each page provides an analysis of a specific topic for better visualization, in addition to an overview page which provides a summary of the dataset and KPIs about the whole dashboard.

A filter that filters the whole dashboard based on the customer status is used for a better understanding of the customers' behavior and analyzes each and its results separately.

The dashboard contains:
 Executive Summary page
 Customer Demographics
 Geographic Analysis
 Service And Churn Analysis
 Customer Satisfaction Score
 Finance & Revenue

# Sample Images
![Screenshot 2024-09-17 190110](https://github.com/user-attachments/assets/ccd4f856-c749-4282-91aa-a80a5af03947)
![Screenshot 2024-09-17 191231](https://github.com/user-attachments/assets/6ff67e7c-a2a7-4db0-b61c-d21c016de3b8)
![Screenshot 2024-09-17 194700](https://github.com/user-attachments/assets/e7e33a8e-4d2f-456a-9f1c-1debc801ad19)
