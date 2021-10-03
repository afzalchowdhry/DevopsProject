# DevopsProject
This repo will contain various ci/cd pipeline

**What tools are being used?**
In this we will see ci/cd using Git Jenkins Ansible and Docker

**High Level**
- Developer will commit the code in Git
- This will trigger Jenkins pipeline job, its going to use maven for the build
- Docker image would be created and uploaded on Docker Hub
- Using Ansible playbook, deploy docker on an Development Server

![image](https://user-images.githubusercontent.com/36516080/135743616-7c98216f-52cf-4624-adc6-dff349cf77a7.png)

**Steps**
- Login to jenkins server and check all required tools like Git (git --version), Maven, Ansible (ansible --version)
