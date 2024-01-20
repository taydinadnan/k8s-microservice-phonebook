# Project Setup Guide

## Description

Phonebook Microservice Web Application aims to create a web application with MySQL Database using Docker and Kubernetes to give the understanding of Microservice architecture. In this application, we have a frontend service and a backend service to interact with database service. Each service will be managed by a Kubernetes deployment. The backend service will be a gateway for the application and it will serve the necessary web pages for create, delete and update operations while the frontend service will serve a search page in order to conduct read operations. To preserve the data in the database, persistent volume and persistent volume claim concepts should be adopted.

## Step 1: Create Docker Image

### 1.1 Clone the Repository
Clone the project repository to your local machine.

### 2 Create Kubernetes YAML Files

1.MySQL Setup (Persistent Volume (PV) , Persistent Volume Claim (PVC), MySQL Deployment, Service, Secret, and ConfigMap)

2.Result Server Setup (Result Server Deployment, Service, and ConfigMap)

3.Web Server Setup (Web Server Deployment, Service, and ConfigMap)