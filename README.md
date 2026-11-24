# Automatic Application Deployment Using Jenkins Master–Slave Architecture

## Project Overview
This project demonstrates automatic application deployment using Jenkins Master–Slave architecture on AWS EC2. Jenkins is configured on the Master instance to coordinate deployment tasks, while the Slave instance is used for remote execution and hosts the application through Apache Tomcat.

## Technologies Used
- AWS EC2
- Linux
- Jenkins
- Java
- Apache Tomcat 9.0.124
- Shell scripting

## Architecture
- **Master:** Jenkins dashboard, job management and build coordination.
- **Slave:** Remote execution environment and application deployment server.
- **Tomcat:** Hosts the deployed sample application on port 8081.

## Deployment Workflow
1. Access Jenkins through the Master EC2 instance.
2. Trigger the deployment job.
3. Jenkins executes the configured tasks on the remote node.
4. The application is deployed to the Tomcat server.
5. Verify the deployed application through the browser.

## Project Documentation
Detailed installation, configuration, deployment steps and screenshots are available in the `Documentation` folder.

## Outcome
Successfully configured Jenkins remote job execution and verified the sample application hosted on Apache Tomcat.

---
*This project was completed as part of hands-on cloud and DevOps learning.*

