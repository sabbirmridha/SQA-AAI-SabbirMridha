# Project Description
A documents search application  / Legal Assistant Application 
## Make sure test environment is ready . Run Below Commands to prepare environment

- download & install docker desktop application
- To Clone the repository :
- git clone https://github.com/AcmeAI-Git/SQA-assignment.git
- Execute below Commands:-
- cd backend 
- docker build -t fastapi-app .
- docker run -p 8000:8000 fastapi-app
  
- cd frontend
- docker build -t react-frontend .
- docker run -p 3001:3001 react-frontend



## API Testing : LegalAssistant-apitesting-newman-report -

- Api testing using Postman and Report Generation with Newman
- HTML Report

# Screenshot
![CaptureNewmanDashboard](https://github.com/user-attachments/assets/63dd2e23-ae0d-4245-bd5d-2df3736b853b)

# Video for api testing report generation with newman
https://github.com/user-attachments/assets/5500b51d-24bb-4a56-95ba-68182e5ee1d3

# Postman Screenshot
![Capture_Postman_CollectionRunner_ApiTesting](https://github.com/user-attachments/assets/985eb54a-d450-45bd-8a63-e4392ee3f369)

# How to run?

- install Node.js
- clone this project directory LegalAssistant-apitesting-newman-report
- To regenerate the report through Newman remove the package.json file first.
- Open the Collection folder in VS Code
- Give following command:
- ``` npm init -y ```
- ``` npm i newman ```

- Change directory to Collection folder and run below command to generate report through newman:-
- ``` npx newman run legalAssistant-testv1.json  ```

---  
## Load Testing : LegalAssistantLoadTest-Jmeter
- Prerequisites: Apache JMeter,JDK 17
- Settings : Set Java Home path in environment variable and Path url in System Variables , Set JMeter Home Path in environment variables & Path url in System Variables.
- Settings Screenshot:
<img width="797" height="651" alt="image" src="https://github.com/user-attachments/assets/01661d08-b367-4335-8788-5f5d5e24e995" />

# LoadTesting Summary:   
- Load test with Jmeter using 100 users per second
- Report generation using Jmx file
# How to run?
- clone this project directory LegalAssistantLoadTest-Jmeter
- Open powershell / gitbash in  the project location
- Now give below commands:
- jmeter -n -t .\Query.jmx -l .\Query.jtl -e -o Reports


# Screenshot for JMeter load test report-
![CaptureJmeterReport](https://github.com/user-attachments/assets/c3cbb453-d540-4329-8781-8e232eedfbd6)

![CaptureLoadTestReportGenerate_Terminal](https://github.com/user-attachments/assets/dd40fc64-8a78-41d5-ab1b-fabdb9716da5)

---
## Web Automation with Cypress : LegalAssistant-WebAutomation-Cypress

# How to run?

- Download the zip folder and unzip it
- Open the project in Vs Code
- Open new terminal
- Give below commands:
  npx cypress run 

# Screenshot for web automation with cypress-

![CaptureAutomationReport_Terminal](https://github.com/user-attachments/assets/ee728b1a-8a83-4453-a9df-c35f6a2f5433)



https://github.com/user-attachments/assets/32b9eb42-cfa5-4d33-b1b3-f2469c0d88e4


