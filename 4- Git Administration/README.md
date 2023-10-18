# Git Administration
## Serving Git Overview
### Git Hosting Options
![Alt text](image.png)
#### Git managed service providers
* Github
* Gitlab (Saas)
* BitBucket
* Microsoft Azure DevOps Repos

![Alt text](image-1.png)

#### Third-party Git Solutions
* GitLab(self-managed)
* GitBUcket
* Gogs
* Gitea

![Alt text](image-2.png)

#### Self-managed server approch
![Alt text](image-3.png)

### Git Protocols
![Alt text](image-4.png)

### Local Git Protocol
![Alt text](image-5.png)

![Alt text](image-6.png)

### Remote Git Protocols
![Alt text](image-7.png)

#### SSH Protocol
![Alt text](image-8.png)

![ ](image-9.png)

#### HTTP/S Protocol
![Alt text](image-10.png)

![Alt text](image-11.png)

#### GIT Protocol specific
![Alt text](image-12.png)

![Alt text](image-13.png)

### Configuring base VM
* create vm instance on cloud provider(aws, azure)
* connect to server instance(ubuntu as an exmaple)
    ``` bash
    ssh -i <...key.pem> username@<DNS-name>
    ```
    - mkdir -p server/repo.git
    - git --bare init
    - cd #back
    - git clone 
* connect to client instance(ubuntu as an exmaple)
    ``` bash
    ssh -i <...key.pem> ubuntu@<DNS-name>
    ```
## Configuring Git for SSH Access
### SSH overview
SSh Approches
* single user 
* multi-user
## Configuring Git for HTTP Access
![Alt text](image-14.png)

### HTTP protocol configuration 
![Alt text](image-15.png)

![Alt text](image-16.png)
