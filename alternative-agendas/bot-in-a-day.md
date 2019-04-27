## LearnAI
# Bot in a Day
Building Intelligent Apps and Agents with LUIS, Azure Search and Azure Bot Service

> Note: This is a recommended **one-day** agenda, with the goal of getting a good mix of Cognitive Services and Microsoft Bot Framework. If you're interested in the full two-day course, please refer to the main [README](../README.md).

## Welcome 

Welcome to Bot in a Day. We will focus on hands-on activities that develop proficiency in Azure Cognitive Services including LUIS and Bing Search. You will also learn to leverage other AI-oriented services such as Azure Search and Azure Bot Services. These labs assume an introductory to intermediate knowledge of these services, and, if this is not the case, then you should spend the time working through the prerequisites.

## Goals

Most challenges observed by customers in these realms are in stitching multiple services together. As such, where possible, we have tried to place key concepts in the context of a broader example. 

At the end of this workshop, you should be able to:

- Understand how to configure your apps to call Cognitive Services
- Build an application that calls various Cognitive Services APIs (specifically LUIS)
- Understand how to implement Azure Search features to provide a positive search experience inside applications
- Configure an Azure Search service to extend your data to enable full-text, language-aware search
- Build, train, and publish a LUIS model to help your bot communicate effectively
- Build and publish an intelligent bot using Microsoft Bot Framework that leverages LUIS and Azure Search

## Prerequisites

This workshop is meant for an AI Developer on Azure. Since this is only a short workshop, there are certain things you need before you arrive.

First, you should have some previous exposure to Visual Studio. We will be using it for everything we are building in the workshop, so you should be familiar with [how to use it](https://docs.microsoft.com/en-us/visualstudio/ide/visual-studio-ide) to create applications. Additionally, this is not a class where we teach you how to code or develop applications. We assume you have some familiarity with C# (intermediate level - you can learn [here](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949) and [here](https://docs.microsoft.com/en-us/dotnet/csharp/quick-starts/)), but you do not know how to implement solutions with Cognitive Services. 

Second, you should have some experience developing bots with Microsoft's Bot Framework. We won't spend a lot of time discussing how to design them or how dialogs work. If you are not familiar with the Bot Framework, you should complete [this tutorial](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0) prior to attending the workshop.

Third, you should have experience with the Azure portal and be able to create resources (and spend money) on Azure. We will not be providing Azure passes for this workshop.

Finally, before arriving at the workshop, please install Visual Studio 2017 (preferred) or Visual Studio Code on your workstation.


## Agenda

Please note: This is a rough agenda, and the schedule is subject to change pending class activities, breaks, and interactions.

- 8-9 (optional): Setup assistance
- 9-10: Introduction and Context for the Course
- 10-11: [Lab 1.5: Developing Intelligent Applications with LUIS][lab-cogsrvc-341]
- 11-12: [Lab 2.1: Developing Intelligent Applications with Azure Search][lab-azsearch-301]
- 12-1: Lunch
- 1-2:30: [Lab 2.2: Building Intelligent Bots][lab-intelbot-301]
- 2:30-4: [Lab 2.3: Enhancing Applications with Bing Search](https://github.com/InsightDI/LearnAI-Bootcamp/blob/master/lab02.3-bing_search/0_README.md)
- 4:30-5: Q&A and Feedback for Bot In A Day
 
## PowerPoint Slides

Download the [Powerpoint slides here](../presentations/). 

## Supplementary materials
Please refer to the main [README](../README.md) that has all of the materials for the two-day bootcamp.

The LearnAI team has provided some extra labs you may be interested in:
- [Lab 2.5: Log Chat Conversations in your Bot](./lab02.5-logging_chat_conversations/0_README.md)
- [Lab 2.6: Testing your Bot](./lab02.6-testing_bots/0_README.md)

## Related courses
Here are some related courses from the LearnAI team:
- [LearnAI: Intelligent Agents: Design and Architecture](https://aka.ms/daaia)
- [LearnAI: Building Enterprise Cognitive Search Solutions](https://aka.ms/csw)  


[lab-cogsrvc-341]: https://github.com/InsightDI/LearnAI-Bootcamp/blob/master/lab01.5-luis/0_README.md
[lab-azsearch-301]: https://github.com/InsightDI/LearnAI-Bootcamp/blob/master/lab02.1-azure_search/0_README.md
[lab-intelbot-301]: https://github.com/InsightDI/LearnAI-Bootcamp/blob/master/lab02.2-building_bots/0_README.md


