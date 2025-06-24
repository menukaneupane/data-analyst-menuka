**Descriptive Analysis**

**Project Description:** Descriptive Analysis of Delayed Payments Impacting Cash Flow

**Project Title:** Understanding Delayed Payment Patterns in the Finance Department

**Objective:** To determine patterns and causes of late payments by analyzing financial transaction data. The aim is to reveal patterns and derive practical insights that can mitigate delays and enhance cash flow.

**Dataset**
Payment Records: PaymentID, CustomerID, InvoiceID, PaymentDate, DueDate, Amount, Status
Invoice Details: InvoiceID, CustomerID, InvoiceDate, Amount
Customer Profiles: CustomerID, Name, Contact Info, Payment Behavior


**Methodology:**
1.	Data Collection and Preparation:
The dataset was loaded using AWS services such as S3 and AWS Glue. Data cleaning procedures addressed missing values, standardized data types, and removed duplicates. To better understand the root causes of business questions, a Fishbone diagram was constructed. The dataset schema was designed to align with business objectives and data normalization standards. A data lake was designed in AWS S3 with appropriate folder structures, tags, and region specifications. VPC, EC2 instances, and Security Groups were configured to ensure a secure and scalable analysis environment.

•	Business problem analysis (Fishbone diagram)



