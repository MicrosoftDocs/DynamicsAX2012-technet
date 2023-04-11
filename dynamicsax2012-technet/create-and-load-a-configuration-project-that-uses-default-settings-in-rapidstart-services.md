---
title: Create and load a configuration project that uses default settings in RapidStart Services
TOCTitle: Create and load a configuration project that uses default settings in RapidStart Services
ms:assetid: f04eed9f-ad8e-41d0-b289-0123a17dbf35
ms:mtpsurl: https://technet.microsoft.com/library/Dn194010(v=AX.60)
ms:contentKeyID: 52348259
author: tonyafehr
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- rapidstart default settings, load project, upload rapidstart data
---

# Create and load a configuration project that uses default settings in RapidStart Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

If you want to quickly configure an implementation of Microsoft Dynamics AX 2012 to use settings and options that Microsoft has identified as the most common for your industry, you can use RapidStart Services to load these default settings into Microsoft Dynamics AX 2012.

For information about when to choose a default configuration project, see [Learn about configuration projects in RapidStart Services](learn-about-configuration-projects-in-rapidstart-services.md).

1.  In your browser, open online services for Microsoft Dynamics ERP at [http://www.dynamicsonline.com](https://go.microsoft.com/fwlink/p/?linkid=141031).

2.  Click **For Customers**, and then click **Sign in**.

3.  Sign in by using the Microsoft account (formerly Windows Live ID) that is associated with your customer account in online services.

4.  If your logon credentials are associated with more than one organization in RapidStart Services, on the **Choose your organization** page, click the name of the organization to work with.

5.  On the Customer Portal dashboard, click **Microsoft Dynamics® RapidStart** to open the RapidStart Services website.

6.  In the main area of the **Getting started** page, click **Create a new project**.

7.  In the **Organization information** area, enter your organization’s name and address, and then, in the **Industry** list, select the name of the industry to which your organization belongs.
    

    > [!IMPORTANT]
    > <P>The country or region that you select determines which global data center is primary for your RapidStart Services access. If you select the incorrect country or region, you can adversely affect the performance times that you experience in RapidStart Services. This selection cannot be changed after you save your entries on the <STRONG>Create a new project</STRONG> page.</P>



8.  In the **Select a configuration option** area, select the **Use a default configuration** option.

9.  Click **Next**.

10. On the **Connection parameters** page, in the **Target Microsoft Dynamics ERP implementation** list, select the name of the Microsoft Dynamics AX 2012 implementation to configure to use default settings.
    
    RapidStart Services attempts to establish a connection to the target implementation that you selected.
    

    > [!NOTE]
    > <P>The connection to your target implementation must be established before you can load data into that implementation. For information about how to create this connection, see <A href="load-configuration-data-into-a-microsoft-dynamics-erp-implementation-from-microsoft-dynamics-erp-rapidstart-services.md">Load configuration data into a Microsoft Dynamics ERP implementation from Microsoft Dynamics ERP RapidStart Services</A>.</P>



11. After the data is tested and validated, click **Load**.

After the data is loaded, you can access a log file that lists the configuration settings and data that have been loaded. You can also open your implementation of Microsoft Dynamics AX 2012. There you can view data that was loaded, make any changes that you require to the default settings, and begin working with important financial functions.

## See also

[Learn about configuration projects in RapidStart Services](learn-about-configuration-projects-in-rapidstart-services.md)

[Create a custom configuration project and specify base information in RapidStart Services](create-a-custom-configuration-project-and-specify-base-information-in-rapidstart-services.md)

[Create a configuration project by copying another project in RapidStart Services](create-a-configuration-project-by-copying-another-project-in-rapidstart-services.md)

[Assign question groups to business experts in RapidStart Services](assign-question-groups-to-business-experts-in-rapidstart-services.md)

[Assign target completion dates to question groups in RapidStart Services](assign-target-completion-dates-to-question-groups-in-rapidstart-services.md)

[Answer questions in a configuration project in RapidStart Services](answer-questions-in-a-configuration-project-in-rapidstart-services.md)

[Review the progress on questions in a configuration project in Microsoft Dynamics ERP RapidStart Services](review-the-progress-on-questions-in-a-configuration-project-in-microsoft-dynamics-erp-rapidstart-services.md)

[Load configuration data into a Microsoft Dynamics ERP implementation from Microsoft Dynamics ERP RapidStart Services](load-configuration-data-into-a-microsoft-dynamics-erp-implementation-from-microsoft-dynamics-erp-rapidstart-services.md)

  


