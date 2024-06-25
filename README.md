# Hands-on Modernization Lab

There is a lot of flexibility in modernization: deploying on-premises, in containers, in OpenShift. In this lab, you will deploy an application, its message queue and database, into Liberty, MQ and Db2 SaaS environments in IBM Cloud.
 
Transformation Advisor will be used to create a migration plan that includes automatically generated configuration files and scripts, guidance and pointers to tools that are needed to accelerate and complete the migration. 
 
This migration plan will include: 
- Details for the MQ administrator to configure the on-premises MQ network
- Details for the Db2 administrator to transfer the data from the on-premises database to the new Db2 SaaS
- Generated Liberty configuration files required to migrate the application

Transformation Advisor can then automatically provision, configure and wire together the Liberty, MQ and Db2 SaaS services to support the application running in the cloud.
 
During the process, you will have the opportunity to utilize the services of WCA4EJA (watsonx Code Assistant for Enterprise Java Applications) to assist with code explanation, code completion, test generation, and also consume the output of Transformation Advisor to convert the application from WebSphere to Liberty.
 
The generated configuration files are then brought into the application environment to build the application for Liberty. Deterministic changes to the application source code can be fixed automatically. Other fixes are facilitated through Generative AI where you can interact in a guided manner with a Java-trained LLM and generated code can be added to the application source.
 
Every time you commit changes in Github, a build will be triggered. You can then review the build, the test results and see details to support promoting the application to the staging environment, and ultimately to production in the Liberty SaaS.

# Steps:

## 1. Download and run the workload discovery tool

## 2. Import results to the Transformation Advisor

### Identify workload topologies
### Select priority sequence of applications and dependencies to modernize
### Explore plan details and actions
### Generate migration plan to provision services and generate configuration files

## 3. Modernize your application

### Start Eclipse IDE and import application from GitHub repo
### Import modernization bundle
### Fix all required changes manually or with Generative AI
### Commit changes to GitHub

## 4. Process results in IBM Liberty SaaS

### View build and test results
### Promote to staging environment to run application
### Promote to production
