# DevOps-Project-Multi-Tier-Bank-Application-Pod-based-Azure

![image](https://github.com/user-attachments/assets/ccfbf474-1151-4a73-a80e-99c0bc1276a3)

Source Code is present in the Azure Repos as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/74bf27b1-e787-4e5f-b48d-0711adc17178)
![image](https://github.com/user-attachments/assets/2fa675ea-635a-4529-879f-48c3d1b79674)

Service Connection is created as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/3d7a6e96-1618-42f5-a542-3bbe6ff24f85)

Azure DevOps Pipelines for bankapp and mysql has been created using the azure-pipelines-bankapp.yaml and azure-pipelines-mysql.yaml as present with this Repository. 
![image](https://github.com/user-attachments/assets/563f6eca-3cd8-4846-ac41-e2ec0e208aa1)

The screenshots for SonarQube, Azure Artifacts Feed after running the pipelines mysql and bankapp is as shown below.
![image](https://github.com/user-attachments/assets/5955032a-aa2a-48a1-9cba-c28b07d7a795)
![image](https://github.com/user-attachments/assets/67a63601-3be0-4e36-8321-d5da3136ab66)

Pod, Service and Deployment for BankApp has been created after successfully running the Azure DevOps Pipelines is shown below.
![image](https://github.com/user-attachments/assets/77a68e10-88ea-4c17-948e-78f00d711ebd)

Entry into the MySQL8 database pods after registrering a new user is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/1673f485-3ce5-4661-9173-0be971fa43c6)
![image](https://github.com/user-attachments/assets/b67a3101-208f-47f1-b2fb-9ccec3bf4f9a)

Entry into Azure DNS Zone is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/1a80fc3e-cb2d-4eac-a876-bf35bc8785d3)

Finally access the bank application as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/b4956bda-1ff9-4ec8-8a0e-62b5de507311)
![image](https://github.com/user-attachments/assets/67ce2930-e70b-421e-ad48-1b4c8338a59a)

```
The bankapp-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry bankapp-auth --docker-server=https://bankappcontainer24registry.azurecr.io --docker-username=bankappcontainer24registry --docker-password=qXXXXXXXXXXXXXXXXrCHXXXXXXXXXXXXXXXXV0zXXXXXXXXXXXX7 -n bankapp
```
<br><br/>
<br><br/>
```
OpenJDK Docker Image is depricated so in this project eclipse-temurin docker image has been used as a base image in the Dockerfile. 
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:-  https://github.com/singhritesh85/Bank-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://github.com/Goldencat98/Bank-App.git
```
