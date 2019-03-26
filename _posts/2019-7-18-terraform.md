---
layout:     post
title:      "Welcome to Terraform!"
categories: blog terraform
---

# Infrastructure as Code with Terraform, Microsoft Azure, VSTS and DSC

## Infrastructure as Code

Today the speed of development is higher then ever and it will be growing. The focus is shifting to cloud where you can easily provision a new environment and move all the changes to production once it is tested. There are plenty of different tools which could help in automating that process and once you've done it right you should not repeat it. There are several benefits in automating your processes. No need to rely on Ops in preparing environment for you. You can do that yourself when needed. No human factor is involved in the deployment. And just think about possibility to use the power of source control in your infrastructure.

I will share my production experience of working with terraform, VSTS and DSC.

## VSTS and Microsoft Azure

I love all the changes which are happening with Microsoft recently. Azure and VSTS provide a lot of benefits for Partners. If you have Visual Studio subscribsion you can set up your source code in VSTS and get it deployed to Azure almost for free:

* Up to 130 free Azure credits per month
* Free usage of VSTS
* Free private build piplines
* Free usage of Test Manager etc.

## Terraform

It is quite easy to use Azure Portal and its friendly interface allow you easily start creating resources. A lot of help describes each step. But that easiness will disappear quite soon. Once you try to move your changes from one environment to the other you will start searching for a way to automate that process. And there are several options which could be used:

1. Azure ARM templates
2. Azure Powershell or Azure CLI
3. 3rd party tools

ARM templates is very powerfull tool to automate your deployments. They can be used to automate almost any resources in Azure RM. But it is quite difficult to modify those te

## DSC

## References

* [VSTS pricing](https://visualstudio.microsoft.com/team-services/pricing/)
* ["Understanding the Difference Between Microsoft Azure and Amazon AWS" by Tim Warner](https://app.pluralsight.com/library/courses/understanding-difference-microsoft-azure-amazon-aws)