**Descriptive Analysis**


**Project Description:** Descriptive Analysis of Delayed Payments Impacting Cash Flow


**Project Title:** Understanding Delayed Payment Patterns in the Finance Department


**Objective:** To determine patterns and causes of late payments by analyzing financial transaction data. The aim is to reveal patterns and derive practical insights that can mitigate delays and enhance cash flow.


**Dataset**
Payment Records: PaymentID, CustomerID, InvoiceID, PaymentDate, DueDate, Amount, Status
Invoice Details: InvoiceID, CustomerID, InvoiceDate, Amount
Customer Profiles: CustomerID, Name, Contact Info, Payment Behavior


**Methodology:**

**1.	Data Collection and Preparation:**

The dataset was loaded using AWS services such as S3 and AWS Glue. Data cleaning procedures addressed missing values, standardized data types, and removed duplicates. To better understand the root causes of business questions, a Fishbone diagram was constructed. The dataset schema was designed to align with business objectives and data normalization standards. A data lake was designed in AWS S3 with appropriate folder structures, tags, and region specifications. VPC, EC2 instances, and Security Groups were configured to ensure a secure and scalable analysis environment.


**•	Business problem analysis (Fishbone diagram)**

![1](https://github.com/user-attachments/assets/09f6e5a0-8de0-4c70-a7aa-692eebe9eedb)
_Figure 1: Fishbone design_


**•	Dataset schema and design planning**

![2](https://github.com/user-attachments/assets/bada7f65-f6f2-4926-b1b0-9033ec13aed9)
_Figure 2: Business question analysis_


 ![3](https://github.com/user-attachments/assets/89aacf40-878b-4d27-b06f-aa679ae1c5ec)
_Figure 3: Data lake design on excel_


**•	Data lake setup (buckets, folders, region, tags)**


 ![4](https://github.com/user-attachments/assets/49f154bc-63aa-477a-b984-83a53f3ec419)
_Figure 4: Data lake design on draw.io_


**•	Infrastructure setup (VPC, EC2, Security Group)**

![5](https://github.com/user-attachments/assets/5b70c8c3-252e-4f47-86ba-185b95526807)
_Figure 5: VPC created_


![6](https://github.com/user-attachments/assets/2fd2692d-b456-4cbd-8966-0210a05822ad)
_Figure 6: Security group created_


 ![7](https://github.com/user-attachments/assets/591872f5-ba7e-454c-849a-82e91b58a59a)
_Figure 7: Instances created_


**•	Documentation of data sources and structure**

 ![8](https://github.com/user-attachments/assets/9c05d35d-e97d-405b-9cfe-735574613c29)
_Figure 8: Documentation of data sources_



**2.	Descriptive Statistics:**

Cost evaluation of dataset ingestion was conducted to measure the efficiency of data storage. The dataset cleaning analysis and design phase were documented. Dataset cleaning implementation executed in the AWS environment with logging and quality checks.

**•	Cost Evaluation of Dataset Ingestion**

 ![9](https://github.com/user-attachments/assets/315ed752-6bab-4dc5-9c38-d9d74b7d5b90)
_Figure 9: Cost Evaluation of Dataset Ingestion_

**•	Dataset Cleaning Analysis and Design**

 ![10](https://github.com/user-attachments/assets/1caa8877-7105-400f-b01c-991ceeadcb2e)
_Figure 10: Dataset Cleaning Analysis & Design for Payment records_

 ![11](https://github.com/user-attachments/assets/8cbc3df9-23ce-4264-b63e-3ee2876b101f)
_Figure 11: Dataset Cleaning Analysis & Design for Invoice details_

 ![12](https://github.com/user-attachments/assets/e3e19ccf-54aa-4046-916c-b5ee562aff80)
_Figure 12: Dataset Cleaning Analysis & Design for Customer Profiles_


**•	Dataset Cleaning Implementation**

 ![13](https://github.com/user-attachments/assets/452622f1-cd71-4214-9901-800ab4b5338f)
_Figure 13: Dataset Cleaning Implementation on DataBrew_

 ![14](https://github.com/user-attachments/assets/4e860366-0e75-4326-a746-7ae321f93f11)
_Figure 14: Dataset Cleaning Implementation for payment record on system_

 ![15](https://github.com/user-attachments/assets/5cfe4a51-cada-4bb0-a1fc-2e891e0b31b8)
_Figure 15: Dataset Cleaning Implementation for payment record on User_

 ![16](https://github.com/user-attachments/assets/7d5424c8-701e-4907-b4b9-0325294d686a)
_Figure 16: Dataset Cleaning Implementation for invoice details on system_

 ![17](https://github.com/user-attachments/assets/901d2914-00c2-4d56-ba44-d7d2ed9950a6)
_Figure 17: Dataset Cleaning Implementation for invoice details on user_



**3.	Data Visualization:**

Cost evaluation of dataset profiling and cleaning supports decision-making in data preparation. ETL Design established workflows for extraction, transformation, and loading. ETL Implementation was completed using AWS services like Glue, Lambda, and S3.  Data cataloging, enriching, and summarization were performed.

**•	Cost Evaluation of Dataset Profiling and Cleaning**

 ![18](https://github.com/user-attachments/assets/3c962794-2bd6-45c4-ad05-b9c3c0d7e09f)
_Figure 18: Cost Evaluation of Dataset Profiling and Cleaning_


**•	ETL Design**


 ![19](https://github.com/user-attachments/assets/c6aa5a38-ba44-4fe1-806b-4c7b81afbd68)
_Figure 19: ETL Analysis on Excel_


 ![20](https://github.com/user-attachments/assets/2469a320-2f6d-48d0-94a8-c1a111c3808d)
_Figure 20: Data Enriching on Excel_


![21](https://github.com/user-attachments/assets/fa94ae39-6c74-4bb8-b206-362207f318cd)
_Figure 21: Data Summarization on Excel_


![22](https://github.com/user-attachments/assets/de676122-4b4b-4e0c-88a7-1d8498cc9dda)
_Figure 22: ETL Design_



**•	ETL Implementation in AWS**

 ![23](https://github.com/user-attachments/assets/29ffd860-23ee-4a96-978e-c125661b6772)
_Figure 23: Alarms created using Cloudwatch_


 ![24](https://github.com/user-attachments/assets/9bca30f5-66aa-44e9-8ec2-3854827ba403)
_Figure 24: ETL Implementation curator bucket on system_


![25](https://github.com/user-attachments/assets/c685feab-09ea-41ac-9d7b-bd7e4e17c168)
_Figure 25: ETL Implementation curator bucket on user_


![26](https://github.com/user-attachments/assets/f82ad2d3-52a6-4f22-9369-341d456d0b91)
_Figure 26: Data Catalog_


![27](https://github.com/user-attachments/assets/ff600547-2ed8-4335-bac0-6d6d3419e894) 
_Figure 27: Data enriching_


 ![28](https://github.com/user-attachments/assets/52f2c7de-2d0f-4e0a-b9b1-71144ecddf2f)
_Figure 28: Data summarization_


 ![29](https://github.com/user-attachments/assets/bbf6fe27-5f00-445f-b13c-1d62fd09dc06)
_Figure 29: Data summarization result_



**4.	Customer Segmentation**

•	Grouped customers based on payment behavior using AWS Glue Data Brew.

•	Segmented them into:

High Risk: >50% delayed payments or avg. delay >15 days

Medium Risk: 20–50% delayed payments

Low Risk: <20% delayed payments


**5.	Insights and Findings**
   
•	Peak delays occurred at month-end 

•	Shorter invoice terms had fewer delays than longer ones. 

•	Digital payments had better on-time rates; delays were common with manual methods.


**6.	Recommendations**


•	Set up auto-reminders before due dates for high-risk clients.

•	Revise terms for frequent defaulters.

•	Encourage digital payments with small incentives.

•	Use dashboards to monitor delay trends and high-risk accounts.

•	Enforce late fee policies for repeated delays.



**Tools and Technologies**

•	Data Analysis: AWS Glue DataBrew, Excel, Pandas

•	Visualization: Tableau / Power BI

•	Storage & Compute: AWS S3, EC2, VPC

•	Cost Analysis: AWS Pricing Calculator


**Deliverables**

•	Cleaned datasets and structured data lake

•	Cost analysis and ETL design documents

•	Visual dashboard (delays, trends, risk zones)

•	Summary report and stakeholder-ready presentation





**AWS Deployment and Service Models**

**•	Objective**

To understand AWS cloud deployment (public, private, hybrid, multi cloud) and service models (IaaS, PaaS, SaaS). The difference between the traditional computing model and the cloud computing model as per their location, access, and privacy.

**•	Tools and Services Used**

AWS Management Console and draw.io.

  
![30](https://github.com/user-attachments/assets/2908fa05-b635-462b-8560-8755a79e7abf)
_Figure 30: Traditional computing model VS Cloud computing model_


 ![31](https://github.com/user-attachments/assets/762cbea7-be4f-4010-8f9f-3b7d7cc5a58b)
_Figure 31: Case study 2_Cloud Deployment Models_


![32](https://github.com/user-attachments/assets/b4f7bb61-2063-4136-bd58-3ddece26704b)
_Figure 32: Case study 2_Diferrence between Public, Private, Hybrid, and Multi cloud_


![33](https://github.com/user-attachments/assets/8e90dc28-d605-4387-8568-029d99c8c0a6)
_Figure 33: Case Study 3_Cloud Service Models_


 ![34](https://github.com/user-attachments/assets/949b3648-4db5-4315-aafb-55253778c38a)
_Figure 34: Case study 3_Diferrence between IaaS, PaaS, and SaaS_

 
 ![35](https://github.com/user-attachments/assets/d1fc74f3-dda6-4607-ac80-70de2b017ae9)
_Figure 35: Knowledge Check Module 1_



**AWS Cost Analysis**

**•	Objective**

To analyze AWS pricing using the AWS Pricing Calculator and Cost Explorer. Understand Total Cost of Ownership - Delaware North and support plan from the case on model 2.

**•	Tools and Services Used**

AWS Management Console, Cost Explorer, and Pricing Calculator 


 ![36](https://github.com/user-attachments/assets/d47929b6-ac1d-4a3b-8584-b3423c35f4ba)
_Figure 36: Case Study 4_Total Cost Of Ownership - Delaware North_


 ![37](https://github.com/user-attachments/assets/ff2de172-3840-4531-ac37-80bbb2d62e19)
_Figure 37: AWS Pricing Calculator_


 ![38](https://github.com/user-attachments/assets/74a589ee-5423-477e-9800-870b40c529bd)
_Figure 38: Case Study 6_Support Plan_


 ![39](https://github.com/user-attachments/assets/58db5998-81f5-4c92-ac52-009b088c7a38)
_Figure 39: Knowledge Check Module 2_



**AWS Global infrastructure** 


**•	Objective**

To explore the difference between Regional Edge Cache, Edge Location, and Region as per their location, access, and privacy.

**•	Tools and Services Used**

AWS Management Console and draw.io


 ![40](https://github.com/user-attachments/assets/41a5e937-7df5-4a94-92a6-96b45d9d9da9)
_Figure 40: Difference between Regional Edge Cache, Edge Location, and Region_


 ![41](https://github.com/user-attachments/assets/e4cb6f77-95a4-4a03-8dc8-37411abbd8aa)
_Figure 41: Knowledge Check Module 3_


**AWS IAM**

**•	Objective**

To understand UCW and AWS responsibility based on EC2, Platform, Software, and Dataset. And to configure secure access control using IAM users and roles.

**•	Tools and Services Used**

AWS Management Console, IAM, and draw.io


 ![42](https://github.com/user-attachments/assets/98d5f886-7a7b-442f-94f6-60ea7805071f)
_Figure 42: Case Study 8_ Responsible of UCW and AWS_


 ![43](https://github.com/user-attachments/assets/234a2a1c-7616-493b-b197-3e03639ad0cb)
_Figure 43: Lab 1-IAM Practice_


 ![44](https://github.com/user-attachments/assets/463fbcb5-b297-4f0d-8099-737f26e939d5)
_Figure 44: Knowledge Check Module 4_



**AWS VPC**


**•	Objective**

To create and manage a secure network using subnets, route tables, and gateways.

**•	Tools and Services Used**

AWS Management Console and VPC


 ![45](https://github.com/user-attachments/assets/2185f911-8cc7-4910-b9d6-98e1331661fe)
_Figure 45: Lab 2-Build your VPC_


![46](https://github.com/user-attachments/assets/623fcf79-2960-48e6-82fd-da4dbf201294)
_Figure 46: Knowledge Check Module_



**AWS Lambda**

**•	Objective**

To build a server less function triggered by S3 events to automate backend processing.

**•	Tools and Services Used**

AWS Management Console, S3, and Lambda


![47](https://github.com/user-attachments/assets/06deccd5-0023-4976-8c85-05bb4f5efe3a) 
_Figure 47: Lab- Create an AWS Lambda function_


 ![48](https://github.com/user-attachments/assets/623f36f3-33b5-4666-8b07-3b2b32dedc98)
_Figure 48: Knowledge Check Module 6_


**AWS EBS**

**•	Objective**

To provision persistent block storage for EC2 and manage snapshots.

**•	Tools and Services Used**

AWS Management Console, EC2, and EBS


 ![49](https://github.com/user-attachments/assets/0a08f37e-f765-4142-935f-86da803cf651)
_Figure 49: Lab 4_Working with Amazon EBS_


 ![50](https://github.com/user-attachments/assets/3a33660d-d1c7-4f0b-b468-33e45bb6123d)
_Figure 50: Knowledge Check Module 7_

