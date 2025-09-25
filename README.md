# XP266 - Experience how to govern the delivery of content in SAP Build solutions

## Description

This repository contains the material for the SAP TechEd 2025 session called XP266 - Experience how to govern the delivery of content in SAP Build solutions.  

## Overview

Learn how to deliver content on SAP BTP in enterprise environments across staged DEV, TEST, and PROD landscapes—through the example of transporting development changes in SAP Build solutions. Gain hands-on experience with the interplay of SAP Content Agent service, SAP Cloud Transport Management service, and the SAP Cloud ALM solution.

## Prerequisites

To complete the exercises in this repository, please make sure that you meet the following prerequisites:

* You have an account on [GitHub](https://github.com/signup).
* You have an [SAP Business Technology Platform (BTP) Account](https://developers.sap.com/tutorials/hcp-create-trial-account.html).

## Exercises

* #### [Exercise 0 - Preparation Steps](exercises/ex0#exercice-0---preparation-steps)

  * [Exercise 0.0 - (Optional) Create a GitHub account](exercises/ex0#exercise-00---optional-create-a-github-account)
  * [Exercise 0.1 - Create a Copy of This Repository](exercises/ex0#exercicse-01---create-a-copy-of-this-repository)
  * [Exercise 0.2 - Login to your BTP subaccount](exercises/ex0#exercise-02---login-to-your-btp-subaccount)

* #### [Exercise 1 - Set up your Delivery Pipeline and Transport Landscape](exercises/ex1#exercise-1---set-up-your-delivery-pipeline-and-transport-landscape)
  * [Exercise 1.0 - Open the Continuous Integration and Delivery Service](exercises/ex1#exercise-10---open-the-continuous-integration-and-delivery-service)
  * [Exercise 1.1 - Add Your Repository in SAP CI CD Service](exercises/ex1#exercise-11---add-your-repository-in-sap-ci-cd-service)
  * [Exercise 1.2 - Create a Webhook](exercises/ex1#exercise-12---create-a-webhook)
  * [Exercise 1.3 - Create a Pipeline Job](exercises/ex1#exercise-13---create-a-pipeline-job)
  * [Exercise 1.4 - Configure the Release Stage](exercises/ex1#exercise-14---configure-the-release-stage)
  * [Exercise 1.5 - Create Transport Landscape in SAP Cloud Transport Management Service](exercises/ex1#exercise-15---create-transport-landscape-in-sap-cloud-transport-management-service)

* #### [Exercise 2 - Maintain your Feature in Cloud ALM](exercises/ex2#Exercise-2---Maintain-your-Feature-in-Cloud-ALM)
  * [Exercise 2.0 - Check your Cloud ALM and cTMS configuration](exercises/ex2#exercise-20---check-your-cloud-alm-and-ctms-configuration)
  * [Exercice 2.1 - Create a new Feature](exercises/ex2#exercise-21---create-a-new-feature)

* #### [Exercise 3 - Transport your pro-code application](exercises/ex3#transport-your-pro-code-application)
  * [Exercise 3.0 - Create a new Development Project in SAP Build](exercises/ex3#exercise-30---create-a-new-development-project-in-sap-build)
  * [Exercise 3.1 - Add additional sample data to your application](exercises/ex3#exercise-31---add-additional-sample-data-to-your-application)
  * [Exercise 3.2 - Release your Changes to GitHub](exercises/ex3#exercise-32---release-your-changes-to-github)

* #### [Exercise 4 - Transport your low-code application](exercises/ex4#transport-your-low-code-application)
  * [Exercise 4.0 - Create a new SAP Build Mobile Project in SAP Build](exercises/ex4#exercise-40---create-a-ne-sap-build-mobile-project-in-sap-build)
  * [Exercise 4.1 - Access Mobile Services and add a new Feature](exercises/ex4#exercise-41---access-mobile-services-and-add-a-new-feature)
  * [Exercise 4.2 - Setup SAP Content Agent Service](exercises/ex4#exercise-42---setup-sap-content-agent-service)
  * [Exercise 4.3 - Create and export a Transport Request in SAP Content Agent Service UI](exercises/ex4#exercise-43---create-and-export-a-transport-request-in-sap-content-agent-service)

* #### [Exercise 5 - Verify all Release Steps](exercises/ex5#verify-all-release-steps)
  * [Exercise 5.0 - Check the Pipeline Job Status](exercises/ex5#exercise-50---check-the-pipeline-job-status)
  * [Exercise 5.1 - Verify Transports created in SAP Cloud Transport Management](exercises/ex5#exercise-51---verify-transports-created-in-sap-cloud-transport-management)

* #### [Exercise 6 - Manage your Feature in Cloud ALM & Deployment](exercises/ex6#exercise-6---manage-your-feature-in-cloud-alm--deployment)
  * [Exercise 6.0 - Manage the lifefcylce of your feature](exercises/ex6#exercise-60---manage-the-lifefcylce-of-your-feature)
  * [Exercise 6.1 - Deploy and monitor changes in your QA and Prod environment](exercises/ex6#exercise-61---deploy-and-monitor-changes-in-your-qa-and-prod-environment)
  * [Exersice 6.2 - Find and access the deployed applications](exercises/ex6#exersice-62---find-and-access-the-deployed-applications)

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2024 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.





Simplify the operational effort behind any cloud solution. This service is a cloud-based automation service within the DevOps portfolio. As a low-code/no-code engine, it is designed to simplify and automate complex manual processes and tasks, enabling DevOps and Operations teams to enhance efficiency and reduce operational overhead by designing and running automation flows.

The service comes with more than 300 built-in automated procedures that cover various DevOps scenarios, including application and database lifecycle management operations, monitoring of application and database health status, root cause analysis, remediation actions, mass operations, and more. By using the low-code/no-code capabilities of this service and its generative AI functionalities, you can also easily create custom commands and tailor every step of the automation to your needs and requirements. Furthermore, the service is highly scalable - it can run hundreds of automations simultaneously, as it is designed to work with low latency even under heavy workload.

The service can execute commands towards different runtimes, services, and third-party tools. Via its REST API, it can also be integrated with any custom application.

### Features

**Run predefined commands**
Select from catalogs dedicated to various DevOps scenarios and trigger ready-to-use commands.

**Create custom commands**
Create your own catalogs with custom commands by reusing the provided content or by chaining, composing, and configuring your custom commands from scratch.

**Back up and restore your content**
Back up your custom content on demand or on a scheduled basis. This enables you to restore your content in the future if needed.

**Store data securely**
Store small amounts of sensitive data in inputs that can be reused across command executions.

**Schedule executions**
Schedule executions to run at a specific date and time or at regular intervals.

**React to events**
Configure executions to be triggered automatically when events are fired from other services, platforms, and applications.

**Generate content with AI**
Generate various types of content with the help of generative AI by providing a simple prompt.

**Operate in private environments**
Perform different types of requests and automate the operation of resources in your private and on-premise environments.

### Multitenancy Support
This service supports multitenancy. It can be used in tenant-aware applications.

The service is available in the following regions:

| Region Name | Region Technical Key | NAT IPs (egress, IPs for requests from Automation Pilot) | LB IPs (ingress, for incoming requests) | API Endpoint | Connectivity Proxy Endpoint |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Europe (Frankfurt) | cf-eu10 | 18.192.167.80, 18.158.182.81, 18.192.94.153, 18.159.0.107, 18.159.145.225 | 3.122.189.245, 3.64.120.107, 3.64.100.186, 52.57.133.101 | emea.autopilot.cloud.sap | connproxy.emea.autopilot.cloud.sap |
| Europe (Netherlands) | cf-eu20 | | | | |
| US East (VA) | cf-us10 | 34.70.41.191, 104.198.247.34 | | amer.autopilot.cloud.sap | connproxy.amer.autopilot.cloud.sap |
| US Central (IA) | cf-us30 | | | | |
| Canada (Montreal) | cf-ca10 | | | | |
| Australia (Sydney) | cf-ap10 | 3.105.105.227, 13.236.234.116, 13.238.123.219 | 54.253.134.59, 52.64.195.197, 13.210.222.4, 52.63.82.125, 13.211.9.192, 13.55.12.174 | aus.autopilot.cloud.sap | connproxy.aus.autopilot.cloud.sap |
| Singapore | cf-ap21 | 20.198.163.232, 20.198.186.35, 20.198.186.35, 20.198.163.248, 20.197.75.244, 20.197.75.129 | | apac.autopilot.cloud.sap | connproxy.apac.autopilot.cloud.sap |
| Japan (Tokyo) | cf-jp10 | | | | |
| KSA (Dammam – KSA Regulated Customers) | cf-sa30 | 34.166.98.117, 34.166.80.109, 34.166.55.178 | | ksa.autopilot.cloud.sap | connproxy.ksa.autopilot.cloud.sap |

For more information, please visit the Help Portal.

**Note:** Business Technology Platform trial accounts in regions Singapore (ap21) and US East (VA) (us10).

**Note:** The service can interact with resources in any region. All you need is to have an instance of the service.

### Service Plans and Metering
This page explains the relationship between the service plans in the Discovery Center and those in the cockpit, and provides information to help you understand how the service is billed.

#### Service Plans
| Service Plan (Discovery Center) | Service Plan (Cockpit: Entitlements) | Service Plan Description |
| :--- | :--- | :--- |
| Standard | standard (Application) | Make full use of the Automation Pilot free tier to explore its features in your testing environment. Only community support is available for free tier service plans and these are not subject to SLAs. |

### Metrics
| Metric | Definition |
| :--- | :--- |
| API Calls (in blocks of 1,000) | Calls made between a customer application or a back-end data source and a cloud service API to send any user action or system action. |

#### Quota Calculation for High-Level Commands
All high-level commands (see Working with Provided Catalogs) are built on top of the core commands mentioned above. Quota usage for these high-level commands can vary significantly, depending mostly on the resource being managed and the specifics of your environment. For example, restarting a small instance will consume less quota than restarting a large productive instance, simply because the process takes more time. Additionally, high-level and custom commands may include complex logic to handle different scenarios or to recover from failures. This dynamic nature means that it’s difficult to estimate quota consumption for these commands in advance - you can see the exact usage only after the execution.

#### Service Specifics
**Quota Calculation for Core Commands**
The service comes with a wide range of provided commands for managing various aspects of the platform. They are built on top of several "core" commands that provide essential functionality. For each of these core commands, quotas (API calls) are calculated in a different way.
