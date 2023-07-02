# Automating Azure integeration into XDR tools

This project is submitted for Future Talent Ready Internship!

# Project Synopsis

## Industry Type
Education-Technology (Ed-Tech)

## Project Title
Automating Azure integration into XDR tools like SentinelOne, Sophos and Splunk.

## Problem Statement/ Opportunity
Creating an Executable script for integrating Threat Intelligence and Analysis, XDR platforms like SentinelOne, and Splunk, into Azure using Azure Blob Storage having endpoint set at GitHub to execute it as and when required by selecting options like - 

            - 1. for SentinelOne, 
            - 2. For Sophos and, 
            - 3. For Splunk.

## Project Description
### The core idea of your project: solving a problem statement / working on an opportunity area?
Creating an Executable script for integrating Threat Intelligence and Analysis, XDR platforms like SentinelOne, and Splunk, into Azure using Azure Blob Storage having endpoint set at GitHub to execute it as and when required by selecting options like -

            - 1. for SentinelOne, 
            - 2. For Sophos and, 
            - 3. For Splunk.

### The problem you are trying to solve and how are you solving it?
This project is useful for people who don't have time to follow official steps for connecting SentinelOne and Splunk into Azure. So, to solve it we created this script to solve the problem around this using Azure Blob Storage functionality along with using GitHub as endpoint for it.

### Mention how your project addresses a clear need, problem, or opportunity and is the solution clearly explained?
This project is useful for people who don't have time to follow official steps for connecting SentinelOne and Splunk into Azure. So, to solve it we created this script to solve the problem around this using Azure Blob Storage functionality along with using GitHub as endpoint for it.

### Is the project’s purpose and basic functionality mapped to the problem statement/opportunity area?
Yes, the project’s purpose and basic functionality is PERFECTLY mapped to the problem statement/opportunity area.

## Primary Azure Technology
      1. Azure DevOps
      2. Azure Blob Storage
      3. Azure Pipelines
      4. Microsoft Sentinel

# To create scripts in Azure using GitHub integration to integrate XDR (Extended Detection and Response) tools like SentinelOne, Sophos, and Splunk, you can follow these general steps:

1. Set up an Azure environment:
   - Create an Azure subscription if you don't have one already.
   - Set up an Azure resource group to organize your resources.
     ![image](https://github.com/aliasgarabidsabunwala/automateazurexdr/assets/67218125/54e3454c-9f4a-4bd2-9a7e-fde7ae48efbf)
   - Provision the necessary Azure services like Azure Functions for executing our scripts.

2. Set up a GitHub repository:
   - Create a GitHub repository to host your scripts.
   - Initialize the repository with a README file and any other necessary files.

3. Create your integration scripts:
   - Determine the specific actions you want to perform with each XDR tool (SentinelOne, Sophos, Splunk) and the corresponding APIs or SDKs provided by each tool.
   - Choose a scripting language like PowerShell or Python to write our scripts.
   - Use the relevant APIs or SDKs to interact with the XDR tools and perform the desired actions.

4. Store your scripts in the GitHub repository:
   - Commit and push your scripts to the GitHub repository.
   - Ensure your scripts are well-documented, including any dependencies and required configurations.

5. Set up Azure Automation:
   - In the Azure portal, navigate to Azure Automation.
   - Create an Azure Automation account if you haven't done so already.
   - Inside the Automation account, create an Azure Automation Runbook.
   - Link the Runbook to your GitHub repository using the GitHub integration in Azure Automation. This integration allows you to automatically pull script changes from the repository.

6. Configure triggers and schedules:
   - Determine the triggers or schedules for executing your scripts. For example, you might want to trigger a script when a new event occurs in one of the XDR tools or run it periodically.
   - Set up the appropriate triggers or schedules in Azure Automation based on your requirements.

7. Test and monitor:
   - Test your scripts by executing them manually or by triggering the associated events.
   - Monitor the execution logs and any outputs or errors generated by the scripts.
   - Iterate and refine your scripts as needed based on the results and feedback.

By following these steps, you can create and manage scripts in Azure using GitHub integration to integrate XDR tools like SentinelOne, Sophos, and Splunk. Remember to consult the documentation and APIs provided by each XDR tool to understand the specific integration capabilities and features available.

# To create scripts in Azure using GitHub integration, you can follow these steps:

1. Set up a GitHub repository:
   - Go to GitHub (https://github.com/) and sign in or create a new account if needed.
   - Create a new repository or select an existing repository where you want to store your scripts.
   - Clone the repository to your local development environment using Git.

2. Set up Azure DevOps:
   - Go to the Azure DevOps portal (https://dev.azure.com/) and sign in or create a new account if needed.
   - Create a new project or select an existing project where you want to manage your scripts.
   - In the Azure DevOps project, go to the "Pipelines" section.

3. Create a pipeline:
   - Click on "New Pipeline" to create a new pipeline.
   - Select the appropriate repository where you cloned your scripts from GitHub.
   - Choose the repository and branch you want to use for the pipeline.

4. Configure the pipeline:
   - Choose the pipeline configuration option that suits your needs. This can include templates, classic editor, or YAML-based configuration.
   - Specify the build steps and tasks required for your script execution. This can include tasks like setting up the environment, installing dependencies, and executing the scripts.

5. Integrate with Azure resources:
   - Within the pipeline tasks, you can use Azure-specific tasks to interact with Azure resources.
   - For example, you can use the Azure CLI task to run Azure CLI commands, the Azure PowerShell task to run PowerShell scripts against Azure, or the Azure Resource Group Deployment task to deploy Azure resources using ARM templates.

6. Define triggers and schedules:
   - Configure triggers and schedules to control when the pipeline should run.
   - Triggers can be set up to execute the pipeline on every commit, on a specific branch, or based on other events.
   - Schedules allow you to specify a recurring time or interval for running the pipeline.

7. Save and run the pipeline:
   - Save the pipeline configuration and trigger a manual run to test the pipeline.
   - The pipeline will fetch the scripts from the GitHub repository, execute the defined tasks, and interact with Azure resources as per the configuration.
