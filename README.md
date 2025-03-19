# **WebProject: Java Web App with AWS CI/CD**  
Welcome to **WebProject**, where I build and deploy a **Java-based web application** using **AWS CI/CD tools**! 🚀  

## **Table of Contents**  
- [Introduction](#introduction)  
- [Project Architecture](#project-architecture)  
- [Technologies Used](#technologies-used)  
- [AWS CI/CD Pipeline](#aws-cicd-pipeline)  
- [Successful Deployment Confirmation](#successful-deployment-confirmation)  
- [Contact](#contact)  
- [Conclusion](#conclusion)  

---

## **Introduction**  
This project is designed as an **introduction to CI/CD** using AWS services. It automates the deployment of a **Java-based web application**, ensuring **continuous integration and delivery**.  

### **Why I Built This Project**  
✅ To gain hands-on experience in **DevOps and AWS CI/CD**.  
✅ To automate the software release cycle **from development to deployment**.  

---

## **Project Architecture**  
The web app follows this **AWS CI/CD architecture**:  

![Architecture](https://github.com/user-attachments/assets/38e82be3-70f2-4f14-84be-0f46ff3bb2c3)  

### **Workflow Summary**  
1. **Development**: Code is written and managed in **Visual Studio Code** inside an **EC2 instance**.  
2. **Version Control**: The source code is pushed to **GitHub** for version control.  
3. **Code Connection**: AWS **CodeConnection** links GitHub to AWS services securely for automatic updates.  
4. **Build & Artifact Management**:  
   - **AWS CodeArtifact** stores dependencies and package versions.  
   - **AWS CodeBuild** compiles and tests the code.  
   - The built artifacts are stored in **Amazon S3**.  
5. **Deployment Automation**:  
   - **AWS CodeDeploy** retrieves the artifacts from **S3** and deploys them to **EC2 Web Servers**.  
6. **Continuous Delivery**:  
   - **AWS CodePipeline** automates the entire workflow from GitHub to deployment.  
7. **Security & Access Management**:  
   - **IAM Roles & Policies** manage secure authentication and authorization across AWS services.  
8. **Infrastructure as Code**:  
   - **CloudFormation Stacks** automate the provisioning of AWS resources.  

---

## **Technologies Used**  

This project integrates several AWS services to **build, test, and deploy** the Java web app efficiently:  

### **🛠 Development & Infrastructure**  
- **Amazon EC2** - Hosts the web app and development environment.  
- **AWS CloudFormation** - Automates infrastructure provisioning.  

### **📂 Storage & Artifacts**  
- **Amazon S3** - Stores the build artifacts for deployment.  
- **AWS CodeArtifact** - Manages application dependencies.  
  - **CodeArtifact Repository** - Stores built packages.  
  - **CodeArtifact Domain** - Manages the repositories.  

### **🔗 Source Control & CI/CD**  
- **GitHub** - Stores and versions the source code.  
- **AWS CodeConnection** - Securely connects GitHub to AWS.  
- **AWS CodeBuild** - Builds and tests the web application.  
- **AWS CodeDeploy** - Automates the deployment to EC2.  
- **AWS CodePipeline** - Orchestrates the entire CI/CD workflow.  

### **🔒 Security & IAM**  
- **IAM Roles & Policies** - Manage permissions for AWS services.  

---

## **AWS CI/CD Pipeline**  
The pipeline automates the deployment of new changes from **GitHub to a live web server**. Here’s how it looks in AWS CodePipeline:  

![CodePipeline Screenshot](https://github.com/user-attachments/assets/57371991-ae76-4975-95d5-9635538503e0)  

---

## **Successful Deployment Confirmation**  
When the deployment is successful, the following message appears on the web page:  

![Web Page Screenshot](https://github.com/user-attachments/assets/81fd351c-9982-4a1c-a199-62b693de4f80)  

---

## **Contact**  
If you have any questions or comments about my CI/CD project, feel free to connect:  

- **LinkedIn**: [My LinkedIn Profile](https://www.linkedin.com/in/joseph-raji/)  

---

## **Conclusion**  
Thank you for exploring this project! I will continue refining the **CI/CD pipeline** and apply these learnings to future projects. 🚀  

---
