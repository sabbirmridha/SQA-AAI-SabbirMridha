# Project Description

## Make sure test environment is ready

- download & install docker desktop application and follow the instruction from the below repository-

   https://github.com/AcmeAI-Git/SQA-assignment.git


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
- ``` npm i newman ```
- Change directory to Collection folder
- ``` npx newman run legalAssistant-testv1.json  ```

  
## Load Testing : LegalAssistantLoadTest-Jmeter

- Load test with Jmeter
- Report
# How to run?
- clone this project directory LegalAssistantLoadTest-Jmeter
- Open powershell / gitbash in  the project location
- Now give below commands:
- jmeter -n -t .\Query.jmx -l .\Query.jtl -e -o Reports

# Screenshot for JMeter load test report-
![CaptureJmeterReport](https://github.com/user-attachments/assets/c3cbb453-d540-4329-8781-8e232eedfbd6)

![CaptureLoadTestReportGenerate_Terminal](https://github.com/user-attachments/assets/dd40fc64-8a78-41d5-ab1b-fabdb9716da5)


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


