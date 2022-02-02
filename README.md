# DevOps Master- Chatbot

## Introduction

DevOps Master Chatbot is a simple chatbot for answering all your questions related to DevOps, Cloud, Cloud platforms such as AWS, Azure, Alibaba, IBM, etc. 
This chatbot was created using Microsoft Azure. Infact this chatbot can also tell you about the tools used in DevOps, like, Terraform, Ansible, GitHub, Maven, shell scripting, python scripting, etc. Using **Azure Cognitive Services** provided by Microsoft Azure and website created by using google sites, makes this amazing chatbot unique. All you have to do is simple ask our chatbot what you want to know.

## Technologies Used

- Microsoft Azure

In this project I have taken **Microsoft Azure** as primary technology.
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. These services and resources include storing your data and transforming it, depending on your requirements. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. It was launched on February 1, 2010, significantly later than its main competitor, AWS.
It’s free to start and follows a pay-per-use model, which means you pay only for the services you opt for.
Interestingly, 80 percent of the Fortune 500 companies use Azure services for their cloud computing needs.


In this project, I have tried to use these following **Azure Cognitive Services** into my project:

1. QnA Maker: QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. QnA Maker doesn't store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in.

2. Knowledge Base: QnA Maker imports your content into a knowledge base of question and answer pairs. The import process extracts information about the relationship between the parts of your structured and semi-structured content to imply relationships between the question and answer pairs. You can edit these question and answer pairs or add new pairs.

3. App Service Plan: An App Service plan defines a set of compute resources for a web app to run. These compute resources are analogous to the server farm in conventional web hosting. One or more apps can be configured to run on the same computing resources (or in the same App Service plan).

4. App Service: Quickly build web apps and APIs in the cloud. Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. You can develop in your favorite language, be it . NET, . NET Core, Java, Ruby, Node.
5. Application Insights: Application Insights is a feature of Azure Monitor that provides extensible application performance management (APM) and monitoring for live web apps. Developers and DevOps professionals can use Application Insights to: Automatically detect performance anomalies. Help diagnose issues by using powerful analytics tools.
6. Search Service: Azure has a unique service offering aptly named “Azure Search”. This is a search-as-a-service cloud solution that lets you add a rich search service to your apps. The search service abstracts the complexities of document retrieval through both a REST API and a . NET SDK.
7. Web App Bot: The Azure Bot resource provides the infrastructure that allows a bot to access secured resources. It also allows the user to communicate with the bot via several channels such as Web Chat.


- Google Sites

Lastly, for creating code free websites on the go, I've used google sites for creating my DevOps website, in which i have deployed my DevOps Chatbot. **Google Sites** is a free website builder from Google. You can create websites with collaborators by giving another Google user edit access. Google Sites are compatible with other Google services like Docs, Sheets, and Slides.


*This repository contains database of question and answer pairs used in knowledge base for the chatbot, and data of the website.* 


