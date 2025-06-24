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


