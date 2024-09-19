# DevOps-Project-Multi-Tier-Bank-Application-Azure

![image](https://github.com/user-attachments/assets/b6fa6716-da6c-491f-8987-294d71f916d6)

Before running the Jenkins Job do the changes for parameters in application.properties file as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/fff6151f-34b6-44d3-9c64-a14c5f26211f)

Create the service connection for Docker Registry, Maven Artifacts Feed and SonarQube. Then run the Azure DevOps Pipeline.

After running the Azure DevOps Pipeline the screenshot for SonarQube, Azure Artifacts Feed and the entry for Azure DNS Zone is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/cd32d0c5-4036-4be4-a113-82792a6d8ce5)
![image](https://github.com/user-attachments/assets/6878a1ba-bf98-4337-8411-bb6736302994)
![image](https://github.com/user-attachments/assets/9cdff5a8-6ad7-4b4e-b659-a6ea98f7dbf9)

Bank Application Pod, Service and Deployment will be created as shown in the screenshot attached below. The entry in MySQL database after registering the user is as as shown below.
![image](https://github.com/user-attachments/assets/1f0f8398-0187-450c-86e4-7b820d36ccc5)

The ingress rule will be created as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/e50fefee-a264-4f3f-b80c-fa95572119e0)

Finally you can access the Bank Application as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/2ae69847-adb5-4d61-97fd-740245389818)
![image](https://github.com/user-attachments/assets/ff1bbdfc-d9e4-4b64-bd87-86d997d72b08)

```
The bankapp-auth secrets for kubernetes can be created using the command below

kubectl create secret bankapp-auth --docker-server=https://bankappcontainer24registry.azurecr.io --docker-username=bankappcontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXOJ7eXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXMtTc -n bankapp
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
<br><br/>
```
Source Code:-   https://github.com/kamalmohan217/Bank-App.git
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
