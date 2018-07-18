---
title: Create questions and question actions in RapidStart Services
TOCTitle: Create questions and question actions in RapidStart Services
ms:assetid: 5cace1d2-2369-4399-a64d-b37c4d360621
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh413234(v=AX.60)
ms:contentKeyID: 36918925
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- create
- questions
- question actions
---

# Create questions and question actions in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

Much of the time that you spend using the **Design** area in Microsoft Dynamics ERP RapidStart Services will be devoted to creating the questions that people in your organization must answer when they use the **Configure** area. The answers that they provide and the data that they upload in response to these questions provide the basis for the configuration that will be loaded into your Microsoft Dynamics ERP implementation.

Use the following procedure to help you create questions for RapidStart Services.

1.  In the RapidStart Services header, click **Design**, and then click **Functional area**.

2.  In the **Functional area** list, select the functional area for which you want to create a question.

3.  In the **Question name group** column, click the name of the question group for which you want to create a question.

4.  Click **New question**.

5.  In the **New question** form, in the **Short name** field, enter a name to identify this question. The short name can contain letters, numbers, and most keyboard symbols. Slashes, pipes, commas, and periods cannot be added to short names.
    
    We recommend that you limit the name to 40 characters, and that you use it to describe the purpose of the question. For example, for the question “Do you want a tax group to be required when a new vendor is created?”, the short name is ”Require tax groups.”
    

    > [!NOTE]
    > <P>This name is used to identify the question when you manage questions in the <STRONG>Design</STRONG> area, such as when you move or delete questions. The name is not displayed in the <STRONG>Configure</STRONG> area.</P>



6.  In the **Question type** area, select a question type. For more information about the available question types and how they can be used, see [Learn about question groups and questions in RapidStart Services](learn-about-question-groups-and-questions-in-rapidstart-services.md).

7.  Click **Create question**.

8.  Use the groups of controls to create the content for the question, to specify how the answers to this question affect other questions in the question group, and to specify what configuration setting will be made when a configuration file is loaded into a Microsoft Dynamics ERP implementation.
    

    > [!NOTE]
    > <P>Depending on the type of question that you are creating, you use three or five groups of controls to define the question. For information about how to use the various groups of controls, see <A href="learn-about-question-groups-and-questions-in-rapidstart-services.md">Learn about question groups and questions in RapidStart Services</A>.</P>



9.  After you configure the question, click **Save**.

## See also

[Learn about question groups and questions in RapidStart Services](learn-about-question-groups-and-questions-in-rapidstart-services.md)

[Create a question group in RapidStart Services](create-a-question-group-in-rapidstart-services.md)

[Edit the text of a question in RapidStart Services](edit-the-text-of-a-question-in-rapidstart-services.md)

[Delete a question in RapidStart Services](delete-a-question-in-rapidstart-services.md)

  


