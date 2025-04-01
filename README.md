Deploy a .NET 8 Web App using Azure App Service with GitHub Integration
Overview
This project demonstrates how to deploy a .NET 8 web application on Azure App Service with automatic deployment from GitHub. The guide covers the entire process from setting up the Azure environment to configuring GitHub integration for continuous deployment.

Prerequisites
Before you begin, ensure you have the following:

An Azure account.

.NET 8 SDK installed on your machine.

Git and a GitHub account.

Azure CLI installed.

A GitHub repository containing your .NET web application.

Steps to Deploy
Step 1: Create an Azure App Service Plan
Log in to the Azure Portal and create a Resource Group.

Create an App Service Plan under the chosen resource group, specifying the region and pricing tier. This plan will host the web application.

Step 2: Create an Azure Web App
Navigate to App Services in the Azure Portal.

Create a new Web App and choose .NET 8 as the runtime stack.

Select the App Service Plan created in Step 1.

Step 3: Configure Deployment from GitHub
In the Azure Portal, go to Deployment Center.

Select GitHub as the source and authenticate to link your GitHub account.

Choose the Organization, Repository, and Branch to connect to the web app.

Select Basic Authentication for secure access.

Step 4: Enable SCM and FTP Authentication
Go to the Configuration section in Azure Web App settings.

Enable SCM Basic Authentication and FTP Basic Authentication for deployment and file management.

Step 5: Verify Deployment
Navigate to Deployment Center and ensure the GitHub deployment process was successful.

Once the deployment completes, browse the Web App URL to verify that the application is live.

Temporary Web App URL
Please note that the Web App URL is temporary and may expire after a certain period since it is hosted on a free Azure account and plan.
For reference:
https://ankitwebapp01-hffxatd8h0gfd5hk.centralindia-01.azurewebsites.net/

Conclusion
This guide outlines the process of deploying a .NET 8 web application to Azure App Service with GitHub integration for continuous deployment. By following these steps, your web app will be automatically updated every time you push changes to your GitHub repository.
