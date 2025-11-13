# 🚀 MuleSoft Anypoint C4E Reports API v1

Welcome to the MuleSoft Anypoint C4E Reports API. This MuleSoft Utility API provides on demand CSV reports on key areas of the Anypoint Platform. It is designed for C4E (Center for Enablement) Leaders, Ops, Architects, Managers who need to audit and report on platform assets, making one HTTP Call and get all resources in all environments in the specified Business Group. Thus including:

Runtime Manager: All deployed applications, their vCore allocations, Mule versions, and statuses.
API Manager: All configured API instances, their backing assets, and contract counts.
Anypoint Monitoring: Reports metrics for all applications including Number of Requests, Performance (percentiles), Error Rates, Average usage on both CPU and Memory 

## 🔑 Authentication
  This API is secured using a Client ID/Secret. You will need to set up a Connected App in your Anypoint Platform then calls these APIs using the X-ANYPNT-CLIENT-ID and X-ANYPNT-SECRET-ID headers

## 🏎️ Getting Started (Quick Start)
  All endpoints require you to specify the Business Group ID you wish to report on AND your configured Connected App (ClientId/ClientSecret) for your Anypoint Platform. Meaning: 

1. Get Credentials: You need to set up a Connected App with the right permissions as described in the Authentication section.
2. Find your Business Group ID: Log in to Anypoint Platform. Navigate to the Business Group you want to query and use the Business Group ID
3. Use Postman to call the APIs or use the included .RAML file
4. Output for all APIs is a CSV file, you will need to copy and paste the CSV in a Spreadsheet (Microsoft or Google) and split by commas. A file where I did 4 calls to my Environment can be seen in the repo
5. Enjoy!


## Disclaimer 
This is not a MuleSoft Product. MuleSoft does not have any responsability over your usage and there is no Support available around it. It's an utility application that helps displaying your Patched dates for applications. Content is my own and not the views of my employer. I am not representing MuleSoft in this content and be cautious
