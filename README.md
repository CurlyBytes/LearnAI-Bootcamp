# Apps & Agents

![Header](./assets/header.png)

## Cognitive Services Bootcamp - Build an Intelligent Search Solution for Images using Microsoft AI Platform

## Important Information - May 2019

This training was created, and last updated, with Bot Framework SDK V4.0, Visual Studio 2017, Bot Emulator 4.3, and .Net Framework 4.6. The content is provided “as is". Due to the rapidly changing nature of the many components, including Azure PaaS services, individual labs may break when new versions are used. Be mindful of this as you progress through them, and test the code with newer versions of the mentioned tools, particularly if you’re planning a redelivery. 

**This repo depends upon the community’s input to keep this training current. As you find inconsistencies and bugs, please update the course! Pull Requests are reviewed monthly and credit appropriately attributed.**

## About this course

In this course, you will focus on hands-on activities that develop proficiency in Azure Cognitive Services including Computer Vision, Custom Vision, LUIS, and Bing Search. 
You will also learn to leverage other AI-oriented services such as Azure Search and Azure Bot Services. 
These labs assume an introductory to intermediate knowledge of these services, and, if this is not the case, then you should spend the time working through the prerequisites. 

Normally used within Intelligent Bots, as LUIS is, the [Q&A Maker](https://www.qnamaker.ai/) service was released after the creation of this training in 2017, so it is not used. We recommend that you search for information and trainings about it.

This training is two days long, but you can compress the content with [alternative agendas](./alternative-agendas/one-day-deltas.md).

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

Firstly, you should have some previous exposure to Visual Studio. We will be using it for everything we are building in the workshop, so you should be familiar with [how to use it](https://docs.microsoft.com/en-us/visualstudio/ide/visual-studio-ide) to create applications. Additionally, this is not a class where we teach you how to code or develop applications. We assume you have some familiarity with C# (intermediate level - you can learn [here](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949) and [here](https://docs.microsoft.com/en-us/dotnet/csharp/quick-starts/)), but you do not know how to implement solutions with Cognitive Services.

Second, you should have some experience developing bots with Microsoft's Bot Framework. We won't spend a lot of time discussing how to design them or how dialogs work. If you are not familiar with the Bot Framework, you should complete [this tutorial](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0) prior to attending the workshop.

Third, you should have experience with the portal and be able to create resources (and spend money) on Azure. We will not be providing Azure passes for this workshop.

Finally, before arriving at the workshop, we expect you to have completed [1_Setup](./lab01.1-computer_vision/1_Setup.md) along with configuring the following for Custom Vision:

1. Training API Key: The training API key allows you to create, manage and train Custom Vision project programmatically

1. You can obtain a key by creating a new project at <https://customvision.ai> and then clicking on the “setting” gear in the top right

## Agenda

Please note: This is a rough agenda, and the schedule is subject to change pending class activities, breaks, and interactions.

- 8-9 (optional): Setup assistance
- 9-10: Introduction and Context for the Course
- 10-11: [Lab 1.5: Developing Intelligent Applications with LUIS](./lab01.5-luis/0_README.md)
- 11-12: [Lab 2.1: Developing Intelligent Applications with Azure Search](./lab02.1-azure_search/0_README.md)
- 12-1: Lunch
- 1-2:30: [Lab 2.2: Building Intelligent Bots](./lab02.2-building_bots/0_README.md)
- 2:30-4: [Lab 2.3: Enhancing Applications with Bing Search](https://github.com/InsightDI/LearnAI-Bootcamp/blob/master/lab02.3-bing_search/0_README.md)
- 4:30-5: Q&A and Feedback for Bot In A Day
 
## PowerPoint Slides

Download the [Powerpoint slides here](./presentations/). 

## Supplementary materials
Please refer to the main [README](../README.md) that has all of the materials for the two-day bootcamp.

The LearnAI team has provided some extra labs you may be interested in:

- [Lab 2.5: Log Chat Conversations in your Bot](./lab02.5-logging_chat_conversations/0_README.md)
- [Lab 2.6: Testing your Bot](./lab02.6-testing_bots/0_README.md)

## Related courses

Here are some related courses from the LearnAI team:

- [LearnAI: Intelligent Agents: Design and Architecture](https://aka.ms/daaia)
- [LearnAI: Building Enterprise Cognitive Search Solutions](https://aka.ms/kmb)  

## Contact

Contact us: learnAI@microsoft.com and <http://aka.ms/LearnAI-GitHub>

## Certifications

The LearnAI team had intense participation in the creation of the following new Microsoft certifications and its required tests:

+ [Azure Data Engineer​](https://www.microsoft.com/en-us/learning/azure-data-engineer.aspx)
  + DP-200: Implementing an Azure Data Solution
  + DP-201: Designing an Azure Data Solutions​

+ [Azure AI Engineer​](https://www.microsoft.com/en-us/learning/azure-ai-engineer.aspx)
  + AI-100: Designing and Implementing an Azure AI Solution

+ [Azure Data Scientist](https://www.microsoft.com/en-us/learning/azure-data-scientist.aspx)
  + DP-100: Designing and Implementing a Data Science Solution on Azure​

## Cognitive Services Compliance

Click [here](https://azure.microsoft.com/en-us/support/legal/cognitive-services-compliance-and-privacy/) to learn how Microsoft Cognitive Services handle your data.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit <https://cla.microsoft.com.>

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
