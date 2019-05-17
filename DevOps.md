## What is DevOps and Role of DevOps
Continuous development & monitoring & testing -> Continuous integration -> continuous deployment
Integrations of:
Plan -> code -> build -> test
Deploy -> operate -> monitor

* **Continuous Development**: planning and coding, Version Control(GIT)
* **Continuous Testing**: testing, Junit
* **Continuous Integration**: auto build, auto test, locate error, Jenkins
* **Continuous Deployment and Monitoring**: 
    **Configuration management**
    * Establish and maintain Application's functional requirements
    * Releasing deployments to servers
    * Scheduling Updates on all servers
    * Maintain Configuration Consistency on all servers
    **Containerization**
    * Maintain the consistency across the environments
    * Use Docker as contain containerization tool
    * Scheduling updates on all servers
    * Maintain Configuration consistency on all servers
    **Monitoring**
    * Monitor the System Performance
    * Monitor the Product overall Performance

## Version Control System (GIT)

**GIT WorkFlow (3 Stages)**
* Working area
* Staging area
* Respository

git config --list
git config --global user.email
git config --global user.name
git init
git status
git add .
git add fileName 
git commit -m "Message"
git log
git log --author="name"
git diff
git diff --staged
git remote add origin url


          Distributed Version Control System

                    GITHUB
            /           |           \          Pull/Push
           /            |            \
          GIT          GIT            GIT
          |             |              |     Commit/Update
          |             |              |
        LOCAL1         LOCAL2         LOCAL3
![Git](GithubWorkFlow.png)

## Continuous Integration (Jenkins)

## Docker Containers

## Docker Networking

## Docker Swarm

## Application Build Tool