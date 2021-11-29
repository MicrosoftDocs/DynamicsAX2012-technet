---
title: Assign question groups to business experts in RapidStart Services
TOCTitle: Assign question groups to business experts in RapidStart Services
ms:assetid: 160c780a-44e3-42b9-9ad7-62311be9fcb7
ms:mtpsurl: https://technet.microsoft.com/library/Dn193987(v=AX.60)
ms:contentKeyID: 52348242
author: Khairunj
ms.author: daxcpft
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- assign questions, business expert
---

# Assign question groups to business experts in RapidStart Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

As the Customer administrator for a configuration project in Microsoft Dynamics ERP RapidStart Services, you assign groups of questions to the appropriate business experts in your organization. The business experts are responsible for answering the questions, and their answers are used to set up your organization’s implementation of Microsoft Dynamics AX 2012.

Business experts who sign in to the RapidStart Services tool have access only to the questions groups that have been assigned to them. By assigning a target completion date to a question group, you can see whether the business expert is making progress to complete the assigned tasks on time.

Before you can assign a business expert to a question group in RapidStart Services, the following prerequisites must be met:

  - The business expert must be added to the organization as a user. To add a business expert as a user, associate the business expert’s Microsoft account (formerly Windows Live ID) with the RapidStart Services service in online services.
    
    For information about how to complete this prerequisite, see [Add users and assign roles in RapidStart Services](add-users-and-assign-roles-in-rapidstart-services.md).

  - The business expert must be assigned to the appropriate role in your RapidStart Services service.
    
    For information about how to complete this prerequisite, see [Add users and assign roles in RapidStart Services](add-users-and-assign-roles-in-rapidstart-services.md).

  - The functional area that contains the group of questions that the business expert has to answer must be included in the template that you are using for your RapidStart Services project.
    
    For information about how to add question groups to functional areas, see [Create a question group in RapidStart Services](create-a-question-group-in-rapidstart-services.md) and [Move a question group in RapidStart Services](move-a-question-group-in-rapidstart-services.md).

After these prerequisites have been met, use this procedure to assign a business expert to a group of questions.

1.  In your browser, open online services at [http://www.dynamicsonline.com](https://go.microsoft.com/fwlink/p/?linkid=141031).

2.  Click **For Customers**, and then click **Sign in**.

3.  Sign in by using the Microsoft account (formerly Windows Live ID) that is associated with your customer account in online services.

4.  If your logon credentials are associated with more than one organization in RapidStart Services, on the **Choose your organization** page, click the name of the organization to work with.

5.  On the Customer Portal dashboard, click **Microsoft Dynamics® RapidStart**.

6.  In the main area of the **Getting started** page, click **Open an existing project**.

7.  On the **Projects** page, click the row of the configuration project in which you want to assign a business expert to a group of questions.
    

    > [!TIP]
    > <P>By default, the project list displays only the projects that you created. To see all configuration projects that have been created for your organization, in the <STRONG>Current view</STRONG> list, select <STRONG>All projects</STRONG>.</P>



8.  In the **Name** column, click the name of the configuration project.
    
    The name of the functional area appears as the title of the next page. This page contains one or more question groups. Each question group appears in its own group box, and a **Mark as complete** button appears at the bottom of each question group box.
    
    The top of each question group box displays the name and status of the question group, the name of the business expert who is currently assigned, and the target completion date, if a date has been assigned.

9.  At the top of each question group box on the page, click the name of the person who is currently assigned to the question group. By default, the name of the person who created the project is used.  
    
    ![Click the name of the person assigned to questions](images/Dn193987.RapidStartQuestionGroupBoxCallout(AX.60).gif "Click the name of the person assigned to questions")   

10. In the **Reassign question group** form, in the **Choose user to reassign this question group to** list, select the name of the business expert who should answer questions in this question group.
    

    > [!TIP]
    > <P>In the <STRONG>Reassign question group</STRONG> form, you can also change the target completion date for the question group.</P>



11. Click **Reassign**.

12. If there is another page of question groups for your configuration project, click **Next** at the bottom of the page to continue assigning question groups.

## See also

[Learn about configuration projects in RapidStart Services](learn-about-configuration-projects-in-rapidstart-services.md)

[Create and load a configuration project that uses default settings in RapidStart Services](create-and-load-a-configuration-project-that-uses-default-settings-in-rapidstart-services.md)

[Create a custom configuration project and specify base information in RapidStart Services](create-a-custom-configuration-project-and-specify-base-information-in-rapidstart-services.md)

[Create a configuration project by copying another project in RapidStart Services](create-a-configuration-project-by-copying-another-project-in-rapidstart-services.md)

[Assign target completion dates to question groups in RapidStart Services](assign-target-completion-dates-to-question-groups-in-rapidstart-services.md)

[Answer questions in a configuration project in RapidStart Services](answer-questions-in-a-configuration-project-in-rapidstart-services.md)

[Review the progress on questions in a configuration project in Microsoft Dynamics ERP RapidStart Services](review-the-progress-on-questions-in-a-configuration-project-in-microsoft-dynamics-erp-rapidstart-services.md)

[Load configuration data into a Microsoft Dynamics ERP implementation from Microsoft Dynamics ERP RapidStart Services](load-configuration-data-into-a-microsoft-dynamics-erp-implementation-from-microsoft-dynamics-erp-rapidstart-services.md)

  


