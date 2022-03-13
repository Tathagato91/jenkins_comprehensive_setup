# Comprehensive Jenkins setup

This repo is merely a collection of my tests conducted using jenkins, and not a project


## Components

- Ansible files for Jenkins installtion

- Jenkinsfile for various pipeline configurations and integrations

- Docker file for Jenkins (with docker installed inside) 

- Jenkins job dsl in groovy script to create freestyle projects in Jenkins. 


## Jenkins files to configure Jenkins pipelines
 
- Create NODE.js multistage Jenkins pipeline with stages like envrionement setup, tests and finally push to docker

- Nodejs multistage pipeline to run tests inside container

- Testing Email Integration enabling continuous feedback

- Testing Slack Integration enabling continuous monitoring

- Testing github integration using Gradle on Docker. Gradle runs on docker container and tests are run within

- Testing Artifactory integration with jenkins for java-spring app with gradle locally installed. The final artifact i.e war file is pushed to jfrog artifactory

- Testing Artifactory integration with jenkins for java-spring app with gradle running on docker container. The final artifact i.e docker image is pushed to jfrog artifactory

***
