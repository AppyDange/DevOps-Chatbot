# Azure Edu-Chatbot: DevOps Master

## Problem Statement: 

Students get confused (basically non-IT ) when it comes to any new technology or any new profession as in DevOps. We are designing an Chatbot which will give all the information about DevOps. "Azure Edu-Chatbot: DevOps Master" is a chatbot which will give out all the necessary information not only of DevOps but also various tools involved in it, to help students getting an basic idea about the profession and many other cloud platforms.

## Description:

In our project we've used many azure services for creating an chatbot for educational purpose which gives information about DevOps, cloud platforms, tools such are Ansible, Maven, Kubernetes, Docker, GitHub, Terraform, etc. This chatbot is built using Azure AI/ML services. QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. With the help of Azure QnA maker we can prebuilt or upload the questionaries for our chatbot. Here, we've used Azure Bot Service to add chatbot to our google site. Azure Bot Service can be added to websites, apps, email, GroupMe, Facebook Messenger, Kik, Skype, Slack, Microsoft Teams, Telegram, SMS, Twilio, Cortana and Skype for Business. In App Service (Web Apps, API Apps, or Mobile Apps), an app always runs in an App Service plan. Azure Application Insight is use it to monitor your live applications. It will automatically detect performance anomalies, and includes powerful analytics tools to help you diagnose issues and to understand what users actually do with your app. It's designed to help you continuously improve performance and usability. Hence with the help of above technologies we have integrated our chatbot to the google site which we have created.


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

## Background working of Azure Cognitive Services:

![Screenshot_20220228-122919 (1)](https://user-images.githubusercontent.com/91502734/155944983-6dc91296-9c99-4a63-92d3-79b7c701a480.jpg)

Here, in the above diagram, explains how cognitive services work in background.  

With the help of Azure QnA maker we have created an knowledge base, then this knowledge base is connected to our azure chatbot and this chat bot is then embedded to our google site DevOps Master --> Client Device sends input to the Bot --> Azure Language understanding understands the client queries and automatically chooses an knowledge base and hence finds the similar answer and sends the output.




## Screenshots:
Step 1: Created an Azure Resource Group named "DevOps"

![Screenshot 2022-02-28 12 48 46](https://user-images.githubusercontent.com/91502734/155941110-00127239-570e-488a-a080-2c1d084aee59.png)

Step 2: Created Azure QnA Maker 

![Screenshot 2022-02-28 13 01 57](https://user-images.githubusercontent.com/91502734/155942231-1e649599-ed30-4132-af9b-d938f105b1aa.png)

Step 3: Created an Azure Knowledge Base:

![Screenshot 2022-02-28 13 03 59](https://user-images.githubusercontent.com/91502734/155942664-ea71c167-16d6-4171-bbeb-0479e80db49b.png)

![Screenshot 2022-02-28 13 04 36](https://user-images.githubusercontent.com/91502734/155942703-eec438fc-2493-40bb-8a0e-fadb9f9d64cd.png)

Step 4: Train the Bot using test feature in Knowledge Base

![Screenshot 2022-02-28 13 05 14](https://user-images.githubusercontent.com/91502734/155942822-4ff34176-02a1-419c-9e70-4d9ee5d45da4.png)

Step 5: Publishing the Bot by creating Azure Bot 

![Screenshot 2022-02-28 13 08 14](https://user-images.githubusercontent.com/91502734/155943077-9bd1223a-4f83-43d0-875d-4f347aea99ed.png)

![Screenshot 2022-02-28 13 09 18](https://user-images.githubusercontent.com/91502734/155943187-f37a55f4-d7e3-45e6-b511-f511e9e2307b.png)

![Screenshot 2022-02-28 13 11 56](https://user-images.githubusercontent.com/91502734/155943525-67acbc66-5278-4350-b9b2-0a29effee092.png)


Step 6: Copying the Embedded code and Secret Key to Google Site to enable our chatbot to work

![Screenshot 2022-02-28 13 10 52](https://user-images.githubusercontent.com/91502734/155943730-300ec70d-a478-4352-9b0f-40666a575b88.png)

![Screenshot 2022-02-28 13 15 47](https://user-images.githubusercontent.com/91502734/155944204-f5029bac-579c-4746-a77e-3461bf95b252.png)

Step 7: Testing on Google Sites if the bot is working or not

![Screenshot 2022-02-28 13 16 50](https://user-images.githubusercontent.com/91502734/155944287-b22c0639-d03d-4aec-96e7-cf213518cd3a.png)


## Project Link: 


https://sites.google.com/view/devopsmaster/home

## Project Demo Video:



*This repository contains database of question and answer pairs used in knowledge base for the chatbot, and data of the website.* 


