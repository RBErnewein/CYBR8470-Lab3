# CYBR8470: Secure Web Application Development
Professor: Dr. Hale  
Student:   Robert Ernewein

## Lab 3: Docker Tutorial

### VM Setup

Platform: ASUS X555D  
Host OS: Windows 10 Home (Build 1903)  
No AMD-V/RVI support

Host VM: VMWare Workstation Pro (v15.5.0)  
Emulating AMD-V/RVI  
VM OS: Ubuntu 20 LTS

### Lab Prerequisites

Create AWS & Docker Hub Accounts
Clone repository: http://github.com/prakhar1989/docker-curriculum

### Install Docker-CE

Pull Busybox  
![](./images/1.busybox.png)

Busybox shell commands  
![](./images/2.bb_shell.png)

Docker run  
![](./images/3.end_docker_run.png)

Remove containers  
![](./images/4.remove_containers.png)

### Static Sites

Pull Static-Site  
![](./images/5.pull_static_site.png)

Static Published Locally  
![](./images/6.static_published.png)

### Dockerfile

Python script  
![](./images/7.Dockerfile.png)

Docker build  
![](./images/8.Docker_build.png)

First build: Catnip  
![](./images/9.First_image.png)

### AWS Beanstalk

Push to repository  
![](./images/10.Docker_push.png)

Published Beanstalk  
![](./images/11.Elastic_Beanstalk.png)

Cleanup  
![](./images/12.Terminate_environment.png)


### Multi-Container Environments

Clone tree  
![](./images/13.FoodTruck_tree.png)

Docker search  
![](./images/14.docker_search.png)

Container logs  
![](./images/15.Container_logs.png)


Curl error  
![](./images/16.curl_error.png)

Curl response  
![](./images/17.curl_memory.png)

Python script  
![](./images/18.Dockerfile.png)

Response timeout  
![](./images/19.rebuild_username.png)

Bash response  
![](./images/20.inspect_bridge.png)

Create bridge network  
![](./images/21.new_network.png)

I had an intermittent error which required me to run docker-compose up -d twice. The foodtruck_web would time out and exit before es was fully up.  
![](./images/23.compose_up.png)

Verified containers on network  
![](./images/24.name_resolution.png)

gpg install and key generation  
![](./images/26.gpg_ecs.png)


### AWS Elastic Container Service

I was unable to complete the final step. Permission issues with the guest account prevented key generation.

![](./images/28.IAM_error.png)

![](./images/29.IAM_error2.png)

![](./images/30.IAM_error3.png)