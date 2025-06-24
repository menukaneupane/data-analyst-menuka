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


•	Business problem analysis (Fishbone diagram)

![1](https://github.com/user-attachments/assets/09f6e5a0-8de0-4c70-a7aa-692eebe9eedb)
_Figure 1: Fishbone design_


•	Dataset schema and design planning

![2](https://github.com/user-attachments/assets/bada7f65-f6f2-4926-b1b0-9033ec13aed9)
_Figure 2: Business question analysis_


 ![3](https://github.com/user-attachments/assets/89aacf40-878b-4d27-b06f-aa679ae1c5ec)
_Figure 3: Data lake design on excel_


•	Data lake setup (buckets, folders, region, tags)

 ![4](https://github.com/user-attachments/assets/49f154bc-63aa-477a-b984-83a53f3ec419)
_Figure 4: Data lake design on draw.io_


•	Infrastructure setup (VPC, EC2, Security Group)

![5](https://github.com/user-attachments/assets/5b70c8c3-252e-4f47-86ba-185b95526807)
_Figure 5: VPC created_


![6](https://github.com/user-attachments/assets/2fd2692d-b456-4cbd-8966-0210a05822ad)
_Figure 6: Security group created_


 ![7](https://github.com/user-attachments/assets/591872f5-ba7e-454c-849a-82e91b58a59a)
_Figure 7: Instances created_


•	Documentation of data sources and structure

 ![8](https://github.com/user-attachments/assets/9c05d35d-e97d-405b-9cfe-735574613c29)
_Figure 8: Documentation of data sources_



**2.	Descriptive Statistics:**

Cost evaluation of dataset ingestion was conducted to measure the efficiency of data storage. The dataset cleaning analysis and design phase were documented. Dataset cleaning implementation executed in the AWS environment with logging and quality checks.

•	Cost Evaluation of Dataset Ingestion

 ![9](https://github.com/user-attachments/assets/315ed752-6bab-4dc5-9c38-d9d74b7d5b90)
_Figure 9: Cost Evaluation of Dataset Ingestion_

•	Dataset Cleaning Analysis and Design

 ![10](https://github.com/user-attachments/assets/1caa8877-7105-400f-b01c-991ceeadcb2e)
_Figure 10: Dataset Cleaning Analysis & Design for Payment records_

 ![11](https://github.com/user-attachments/assets/8cbc3df9-23ce-4264-b63e-3ee2876b101f)
_Figure 11: Dataset Cleaning Analysis & Design for Invoice details_

 ![12](https://github.com/user-attachments/assets/e3e19ccf-54aa-4046-916c-b5ee562aff80)
_Figure 12: Dataset Cleaning Analysis & Design for Customer Profiles_


•	Dataset Cleaning Implementation

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

