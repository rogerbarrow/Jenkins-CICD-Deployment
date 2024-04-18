# Jenkins-CICD-Deployment
# Install Jenkins
*Create a EC2 in AWS and SSH into the Server the Public IP Address
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/e0b02ead-47f1-4a3b-a13c-cb4e8f284423)
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/bc2f9968-06d5-4288-ab0b-e03bb0ec1d6c)
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/31a1672f-6da1-4019-93e8-d977a7e7c8c1)
# Now that your login into the instance lets install the required dependencies
  * sudo apt update
  * sudo apt install openjdk-11-jre
  * Verify Java is install withe cmd java--version
  ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/c174a29b-7e7a-4b62-9e9a-b930dbd1ccd2)
# Now we will install Jenkins
 * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/52a01652-86a6-4adb-8cb4-89ed066e45c2)
 * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/88201736-8483-4276-bc4d-09b64c7d5130)
# Jenkins Server runs on port :8080 we Will need to Edit the Security Group in your EC2 to give access
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/83e78568-8bcc-47c9-a0a8-a3ca31e1e822)
   * Login to jenkins
   * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/0a3bfc22-aa42-4b85-8372-1d3704b0f18a)
   * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/7230ac5c-b99c-4ab2-8e1c-7279d33172a0)
# Next Step is install Docker 
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/598a7580-d41c-49ad-9896-7a996e9f55eb)
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/acc4fbbc-e9f5-43ce-8d54-d16845f1917d)
  * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/86e7a66e-3c92-4c4a-88e4-d7af7cc0eabb)
# Install the Dokcer Pipline Plugin in Jenkins:
 * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/69ae2bd9-1761-4bd6-83f0-4f506a6c3b38)
 * ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/e0d7b6b2-97d8-4a37-9419-e08767f4167e)
# Build your Jenkins Pipeline
*![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/2a878806-3f20-46c6-acb1-9d0e9c5b4a8e)
* ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/1207076e-4745-487e-8ef2-6018b687a186)
* ![image](https://github.com/rogerbarrow/Jenkins-CICD-Deployment/assets/46138186/ad7ae6b9-e612-404d-8c76-10fe50e60c75)





#Set up CICD
#Deploy application on K8
