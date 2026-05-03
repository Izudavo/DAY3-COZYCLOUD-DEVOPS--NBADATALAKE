# NBA Data Lake 

## **Project Overview**
This project is serves as a storage solution to store NBA team scores standings for the season 2025 using the following AWS services **Amazon S3 for storage**, **AWS Glue to extract, transform to json, load into catalog data**, **Amazon Athena service to directly query the data stored in the data lake using SQL ** and **sportsdataio** to provide nba stats. The project was written in Python, to understand and carry out handson experience on Devops Practices and AWS Cloud Infrastructure tools.

---

## **Features**
- Fetches NBA standings 2025 from sportdataio.
- AWS Glue extracts and transforms this into a datalake catalog.
- AWS Athena a serverless service, runs the SQL querry of the datalake catalog.
- S3 stores this data for future reference and download.
- Designed with security in mind, following the principle of least privilege for IAM roles.

## **Prerequisites**
- Free account with subscription and API Key at [sportsdataio]
- Personal AWS account with basic understanding of AWS and Python scripting.

---

## **Technologies**
- **Cloud Provider**: AWS
- **Core Services**: S3, GLUE, Athena
- **External API**: NBA Game API (sportsdataio)
- **Programming Language**: Python 3.x
- **IAM Security**:
  - Least privilege policies for S3, GLUE, Athena

---

## **Project Structure**
```bash
DAY3-COZYCLOUD-DEVOPS--NBADATALAKE/
├── policies/
│   ├── IAM_Role         
├── src/
│   ├── .env           
│   ├── delete.py  
│   └── setup_nba_data_lake.py
├── delete_aws_resources/

      

```

## **Setup Instructions**

This project walk through was guided from Alahl1,

### **Challenges**

Had a little bit of hurdles deploying on the AWS Cloudshell which was used for used for this project, but using GitBash i was able to walkthrough and deployed!

A screenshot of AWS SNS alert received from the API call is attached to this repo.

Glad to be a part of this CozyClod_DevopsAllStarsChallenge_Crew, Kudos once again!!!
