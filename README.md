# FinalProject
### 1.Brief description of project
#### The main idea of the project is to organize a consistent transfer of changes made by the site developer to the infrastructure, that is, the organization of the CI / CD process for delivering the changed code to the infrastructure. The following components have been implemented:
- Developer interaction with GitHub;
- Transferring data to Jenkins;
- Performing actions on an agent;
- Data transfer to web server;
- Automation with Ansible.
#### Additionally, a host with Ansible was created to be able to automatically deploy the environment based on the created infrastructure. At this point, a script has been written to create a website based on the developer machine. Scripts can be combined into a bash file for later automatic launch on Ansible.
The next steps in the development of the project are the addition of automatic infrastructure configuration and the creation of test environments.
### 2.Links
[GitHub repository](https://github.com/OleksandrZhabko/Jenkins_test.git)

[Presentation]()

[Site](http://ec2-3-19-225-253.us-east-2.compute.amazonaws.com/)
### 3. Project implementation screenshots
#### Scripting and setting up a secure session on GitHub:
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/git_1.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/git_2.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/git_3.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/git_4.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/git_5.jpg)
#### Creating hosts using AWS:
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/aws_1.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/aws_2.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/aws_3.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/aws_4.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/aws_5.jpg)
#### Configuring Jenkins for automatic code deployment to a web server:
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_1.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_2.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_3.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_4.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_5.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_6.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_7.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_8.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_9.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_10.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/jenkins_11.jpg)
#### An example of a developer changing the code and automatically deploying it to the server:
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_1_before.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_2.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_3.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_4.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_5.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_6.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_7.png)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/web_8.png)
#### Configuring Ansible:
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/Ansible_1.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/Ansible_2.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/Ansible_3.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/Ansible_4.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/Ansible_5.jpg)
![alt text](https://github.com/OleksandrZhabko/FinalProject/blob/main/images/Ansible_6.jpg)
