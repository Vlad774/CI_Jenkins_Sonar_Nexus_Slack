# Continuous Integration with Jenkins, SonarQube, Nexus on AWS with Slack Notifications
## Description

This project establishes a robust Continuous Integration (CI) pipeline utilizing Jenkins, SonarQube, and Nexus, all deployed on AWS infrastructure. The integration of Slack notifications ensures real-time communication of build statuses to the development team. The primary objective is to automate the build, test, and analysis processes, thereby enhancing code quality and streamlining artifact management.

## Technologies

- CI/CD Orchestration: Jenkins
- Code Quality Analysis: SonarQube
- Artifact Repository Management: Nexus Repository Manager
- Cloud Infrastructure: Amazon Web Services (AWS)
- Notifications: Slack
   
## Architecture Overview

- Jenkins CI Server: Hosted on an AWS EC2 instance, Jenkins automates the pipeline by fetching code from the version control system, 
  initiating builds, running tests, and deploying artifacts.
- SonarQube Integration: During the pipeline execution, Jenkins interfaces with SonarQube to perform static code analysis, ensuring 
  adherence to quality standards.
- Nexus Repository Management: Post-build, Jenkins publishes the generated artifacts to Nexus, facilitating efficient dependency 
  management and artifact storage.
- Slack Notifications: Upon completion of each pipeline stage, Jenkins sends real-time notifications to a designated Slack channel, 
  keeping the development team informed of build statuses and any issues that arise.
- AWS Infrastructure: The entire setup leverages AWS services, ensuring scalability, reliability, and security for the CI pipeline 
  components.
  
  

## Walk-through:


 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/Diagramm.png) 
 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/AmazonMQ.png) 
 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/EC2.png)
 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/ENV.png)
 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/RDS.png)
 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/cloudfront.png)
 ![First try](https://github.com/Vlad774/AWS_Rearch_Web_App_on_Cloud_PAAS_SAAS/blob/main/memcaches.png)
 


