

---

## Proforma invoice Portal

This is a development project of a Web Portal to create a proforma invoice based upon Service Delivery outcomes

Web Portal System for the automated creation of a pro-forma invoice by extracting info via client’s Service Management Platform API to consolidate info regarding incidents resolved, service requests completed and monthly fixed billing line items onto the resulting PDF document which is then uploaded to client’s billing system for validation and ingestion.

---

### Description

This project consist of a number of AWS platforms and components as follows:
1This project consists of a number of AWS platforms and components as follows:
1. Single VPC - Shared services
2. Multiple EC2 instances (Django Portal, Aurora DB, Strongswan host etc. )
3. An API Gateway
4. Lambda functions
5. Multiple S3 buckets
---

### Architecture

The System Architecure is depicted below:

<img src="./proforma.jpg">

---

The system works as follows:
1. 
---

API Gateway to S3 bucket data flow

<img src="./CDRInfo.png">
   
---

S3 bucket to Aurora DB flow

<img src="./sipgrafana.png">

---
