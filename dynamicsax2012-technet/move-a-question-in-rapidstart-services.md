---
title: Move a question in RapidStart Services
TOCTitle: Move a question in RapidStart Services
ms:assetid: 24d5adc6-4744-420a-ac03-1312e0f9f706
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh413227(v=AX.60)
ms:contentKeyID: 36918918
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- move
- question
---

# Move a question in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

In Microsoft Dynamics ERP RapidStart Services, you can move a question from one question group to another group in the same functional area or to a question group in a different functional area.

If the question that you are moving includes a dependency or a lookup, this association will be removed. Before you finish moving a question, RapidStart Services displays a list of dependencies or lookups that will be removed when the question is moved. You can create or restore any required dependencies or lookups after you move the question.


> [!NOTE]
> <P>You cannot move questions that belong to a published functional area. For information about how to unpublish a functional area, see <A href="unpublish-a-functional-area-in-rapidstart-services.md">Unpublish a functional area in RapidStart Services</A>.</P>



1.  In the RapidStart Services header, click **Design**, and then click **Functional area**.

2.  In the **Functional area** list, select the functional area that contains the question that you want to move.

3.  In the **Question group name** column, click the row of the question group that contains the question that you want to move.
    

    > [!TIP]
    > <P>Do not click in the <STRONG>Question group name</STRONG> column. Doing so opens the page that is used to create and update questions.</P>



4.  Click the **Question group** button, and then click **Move question**.

5.  In the **Move question** form, in the **Target functional area** list, select the name of the functional area to which you want to move one or more questions.

6.  In the **Target question group** list, select the name of the question group to which you want to move one or more questions.

7.  Below the name of the source question group, select the name of a question that you want to move, and then click **Add \>\>**.

8.  Repeat step 7 for each question that you want to move.

9.  Click **Next**, and then review your selections.
    

    > [!TIP]
    > <P>We recommend making a note of any questions for which dependency or lookup associations will be removed so that you can restore the associations if you want to.</P>



10. Click **Finish**.

## See also

[Learn about question groups and questions in RapidStart Services](learn-about-question-groups-and-questions-in-rapidstart-services.md)

[Create questions and question actions in RapidStart Services](create-questions-and-question-actions-in-rapidstart-services.md)

[Edit the text of a question in RapidStart Services](edit-the-text-of-a-question-in-rapidstart-services.md)

[Delete a question in RapidStart Services](delete-a-question-in-rapidstart-services.md)

  


