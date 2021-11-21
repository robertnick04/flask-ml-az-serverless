
# Azure CI/CD

# Overview
This project titled 'Building a CI/CD Pipeline' project is part of the 'DevOps Engineer for Microsoft Azure' Udacity nanodegree program.

The objective of this project is to :

A. Create an Azure pipeline.

B. Deploy the python app (provided in the project resource) in Azure cloud.

C. Test and validate that the pipeline deploys the code changes.

The following steps will implement the task of building a CI/CD pipeline:
Note: The goal of the python application in this project is to predict housing prices in Boston. 

1. Create a github repository and upload the starter code to it.
2. Create a workflow using Github Actions and deploy the app in Azure cloud.
3. Create a CI/CD pipeline in Azure DevOps and deploy the app using Azure pipeline in Azure App service.
4. Run Flask app and validate the results (prediction).
5. Perform load test using locust and note the results.
6. Make sure Code changes committed to the GitHub repo would trigger automated code deployment. 

### High level Architecure 

Az_CICD_Architecture.png![image](https://user-images.githubusercontent.com/34904900/142768949-611a162c-4713-478c-8e09-3fc06e2bf027.png)


Project Timeline Trello board - https://trello.com/b/1cuoVD4k/azcicd

Project Timeline Spreadheet - https://github.com/robertnick04/flask-ml-az-serverless/blob/main/AzureCICD_project_timeline.xlsx

Project Demo Video - https://www.youtube.com/watch?v=jvwVc1S0qDo&t=23s

[![CI](https://github.com/robertnick04/azure-cicd/actions/workflows/main.yml/badge.svg)](https://github.com/robertnick04/azure-cicd/actions/workflows/main.yml)

#### 1. Connect to the Cloud shell from the terminal and clone the project repository

![Screen Shot 2021-09-23 at 5 31 43 PM (2)](https://user-images.githubusercontent.com/60614362/136077416-06f5238a-8c91-479f-8d37-f7ee076d72f3.png)

#### 2. Install requirements for python virtual environment

![Screen Shot 2021-09-23 at 5 47 18 PM (2)](https://user-images.githubusercontent.com/60614362/136077432-ab04c1e0-1916-4f09-aae2-150582d62ac8.png)

#### 3. Build using Github actions

![Screen Shot 2021-09-23 at 5 56 16 PM (2)](https://user-images.githubusercontent.com/60614362/136077452-6d2da0a4-b9e0-482b-80bd-6ee6a74b8b53.png)

#### 4. Validate app is deployed successfully using Github actions and the app is running

![Screen Shot 2021-09-23 at 6 34 13 PM (2)](https://user-images.githubusercontent.com/60614362/136077481-bd85f256-aa1a-48cb-8ce4-b16b42ac4129.png)


#### 5. Setup CI with Azure pipelines

![Screen Shot 2021-09-23 at 6 46 37 PM (2)](https://user-images.githubusercontent.com/60614362/136077496-266d311e-919c-4086-a065-29f52d042e51.png)

#### 6. Deploy the app using Azure pipeline

![Screen Shot 2021-09-24 at 4 05 30 PM (2)](https://user-images.githubusercontent.com/60614362/136077528-a1a67e87-03f3-4915-b39b-dbbdbadc060e.png)

#### 7. Validate app is deployed successfully using Azure pipeline and the app is running

![Screen Shot 2021-09-24 at 4 05 05 PM (2)](https://user-images.githubusercontent.com/60614362/136077511-dd84f4b4-bb37-4ec9-9cf6-df76fa2aa583.png)

#### 8. Run the 'make prediction' script and validate the result

![Screen Shot 2021-09-24 at 4 06 08 PM (2)](https://user-images.githubusercontent.com/60614362/136077556-c6a27c04-f8e2-405c-861b-07a3366560b3.png)


#### 9. Validate the prediction

![Screen Shot 2021-09-24 at 4 08 05 PM (2)](https://user-images.githubusercontent.com/60614362/136077565-7da5dad5-5aae-45c1-90cd-c17284e580cb.png)

#### 10. Tail the log 

![Screen Shot 2021-09-24 at 4 10 00 PM (2)](https://user-images.githubusercontent.com/60614362/136077574-1d74c0f6-9f1a-4bc1-994a-ab84038984c2.png)

#### 11. Run the load test using locust

![Screen Shot 2021-11-18 at 4 43 07 PM](https://user-images.githubusercontent.com/34904900/142501851-ef3f6c5f-496f-48d9-b063-e09fe7e28198.png)

![Screen Shot 2021-11-18 at 4 42 58 PM](https://user-images.githubusercontent.com/34904900/142501878-dbf3f907-1e6c-4148-aa03-1e309269f821.png)

## Future Improvements
This project could be enhanced by including the following items:
- PROD and NON-PROD environments such as Dev, test/stage could be implemented.
- A policy could be implemented to require Pull requests are reviewed and approved before merging the code to the main branch



