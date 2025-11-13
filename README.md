# 🚀 MuleSoft Anypoint C4E Reports API v1

Welcome to the MuleSoft Anypoint C4E Reports API. This a MuleSoft API
The MuleSoft Utility API that provides you with on demand CSV reports on key areas of the Anypoint Platform, designed for C4E (Center for Enablement) Leaders, Ops, Architects, Managers who need to audit and report on platform assets across areas of the Anypoint Platfrom by making one HTTP Call then getting all the MuleSoft resources in all the environments in the specified Business Group. 

Reports currently cover: 
- Runtime Manager: All deployed applications, their vCore allocations, Mule versions, and statuses.
- API Manager: All configured API instances, their backing assets, and contract counts.
- Anypoint Monitoring: Reports metrics for all applications including Number of Requests, Performance (percentiles), Error Rates, Average usage on both CPU and Memory

Use Cases:
- I want to find all the API Instances that are Inactive or Unmanaged, so that I can delete them and save costs on licenses
- I want to find potential duplicates
- I want to find APIs that are not being used enough or at all (Number of Requests, CPU/Memory, etc.)
- I want to control the amount of vCores my Runtime Manager APIs are using 

## Example CSV Outputs in a Spreadsheet 
<img width="2014" height="900" alt="image" src="https://github.com/user-attachments/assets/830cb8ac-b130-4ac0-9e0a-39e1690939b7" />
<img width="1939" height="927" alt="image" src="https://github.com/user-attachments/assets/3a4008aa-02b5-4c7d-920e-c3522786720b" />
<img width="2016" height="895" alt="image" src="https://github.com/user-attachments/assets/5eb25877-87e3-48de-a915-451af397e566" />


## 🏎️ Getting Started (Quick Start)

You will need an Anypoint Account with the right permission and the ability to set up Connected Apps

1. Get Credentials: You need to set up a Connected App with the right permissions as described in the Authentication section.
2. Find your Business Group ID: Log in to Anypoint Platform. Navigate to the Business Group you want to query and use the Business Group ID
3. Import the Postman Collection and the Postman Environment. Add your credentials to the Postman Environment.  
4. Clone the repo
5. Import the MuleSoft Application folder [Anypoint-C4E-Reports-API]([url](https://github.com/angelalbericisfdc/anypoint-c4e-reports/tree/main/Anypoint-C4E-Reports-API)) into Anypoint Studio or ACB and run it!  
6. Use Postman to make the calls to your local server 
7. Output for all APIs is a CSV file, you will need to copy and paste the CSV in a Spreadsheet (Microsoft or Google) and split by commas. A file where I did 4 calls to my Environment can be seen in the repo
8. Done you got the data! 





## Disclaimer 
This is not a MuleSoft Product. MuleSoft does not have any responsability over your usage and there is no Support available around it. It's an utility application that helps displaying your Patched dates for applications. Content is my own and not the views of my employer. I am not representing MuleSoft in this content and be cautious
