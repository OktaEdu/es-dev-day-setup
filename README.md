# Developer Day 2021 Lab: Deploy a custom SPA app with Terraform
In this lab, you will leverage 3 Terraform configurations to deploy a Single Page App (SPA).
## Overview
Create and deploy your custom app in less time with fewer errors using sample code and Terraform automation provided by Okta. In 90 minutes or less, you’ll learn how to do user mappings and assignments, and deploy your app into production. Easily tweak what you learn for your other apps. Developers, DevOps, and DevSecOps will benefit from this lab that showcases a typical CIAM use case.
## Prerequisites
- [Developer](https://developer.okta.com/signup/) or Sandbox org
- [ASA Team](https://app.scaleft.com/p/signupV2) with provisioning enabled
- [ASA Client](https://help.okta.com/asa/en-us/Content/Topics/Adv_Server_Access/docs/sft.htm)
- [Terraform](https://www.terraform.io/downloads.html)
- [Git command-line client](https://git-scm.com/downloads)
- Bash (Linux, MacOS or Git Bash)
- [AWS account](https://aws.amazon.com/free) (non-production)
- [Node.js](https://nodejs.org/en/download/) (optional)


## Setup Tasks
You will need to do the following preparation to be ready to complete the Developer Day Lab:
### Okta Org
1. Login as an admin (at least app and org admin)
2. Create an API token
3. Save the API token value
4. Create a group called "ASA Access"
5. Add yourself to the new group
6. Add the Advanced Server Access application
### ASA
1. Create a new ASA team integrated with your Okta Org as the IDP
2. Enable API provisioning in the ASA app
3. Assign the ASA Access group to the app
4. Push the ASA Access group to ASA
5. In ASA, create a service user
6. Create an API key for the service user and save the key and secret
7. Assign the new service user to the Owners group
### AWS
1. Create a new IAM user on your non-production account that is API access only
2. Assign the IAM user to a group including EC2Full and VPCFull access
3. Creat an API key for the IAM user and save the key and secret

## Credentials
You will need to have the following credentials handy in order to complete the lab:
### Okta Org
- Org name
- Org base URL (i.e. oktapreview.com or okta.com)
- API Token
### ASA
- API Key
- API Secret
- ASA Team Name
### AWS
- Access Key
- Secret Key
