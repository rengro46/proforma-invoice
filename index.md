

---

## Proforma invoice Portal

This is a development project to create a Web Portal to create a proforma invoice based upon Service Delivery outcomes

Web Portal System for the automated creation of a pro-forma invoice by extracting info via client’s Service Management API, using a Python Panda to consolidate info regarding service requests and monthly fixed billing line items onto the resulting PDF document which is then uploaded to client’s billing system for validation and ingestion.

---

### Description

This project consist of a number of AWS platforms and components as follows:
1This project consists of a number of AWS platforms and components as follows:
1. Single VPC - Shared services
3. Multiple EC2 instances (Grafana, Django Portal, Aurora DB, Strongswan host etc. )
4. An API Gateway
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