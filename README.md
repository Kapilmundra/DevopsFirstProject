# Automation using Jenkins 
 
## Project_Description
Automation using Jenkins and Docker container 

https://www.linkedin.com/posts/kapil-mundra-2a7960194_devopsassemblyline-devopsfirstproject-projectabrdescription-activity-6664037495480569858-Ex0O

## Job1_Production
Connect to master branch in repository on GitHub , It will keep on checking and if any commit made it will copied to production server using docker 

## Job2_Developer
Connect to dev branch in repository on GitHub , It will keep on checking and if any commit made it will copied to testing server by using docker

## Job3_Testing
checking the testing server site working

## Job4_Merging
It will run by Quality Assurance Team manually after checking test server working fine. This job will merge both branches at github and automatically trigger Job 1
