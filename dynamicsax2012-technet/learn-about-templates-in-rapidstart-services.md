---
title: Learn about templates in RapidStart Services
TOCTitle: Learn about templates in RapidStart Services
ms:assetid: 6264ab73-3dd0-42b8-b6c2-32d2f0001f20
ms:mtpsurl: https://technet.microsoft.com/library/Hh413235(v=AX.60)
ms:contentKeyID: 36918926
author: tonyafehr
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- templates
- RapidStart Services
---

# Learn about templates in RapidStart Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

When you configure an implementation of Microsoft Dynamics AX 2012 by using Microsoft Dynamics ERP RapidStart Services, the configuration is based on a template that is provided by Microsoft or that you create yourself. A template contains information about the configuration in the form of one or more functional areas. A template is the container to which you add information about the configuration in the form of one or more functional areas. Functional areas are used to aggregate groups of questions that relate to specific areas of the implementation.

For example, “Process customer payments” is a functional area that is provided by default in RapidStart Services. This functional area contains question groups that include questions about customer payments, customer payment sales taxes, and credit card payments. The functional area “Manage fixed assets” consists of question groups that address depreciation, acquisition, and fixed assets. The answers to these questions help determine how customer payments and fixed assets are configured in Microsoft Dynamics AX 2012.

As Figure 1 shows, each functional area in a template consists of one or more question groups and the questions in those groups.

![RapidStartServices Complex Hierarchy](images/Hh413235.RapidStartServicesComplexHierarchy(AX.60).gif "RapidStartServices Complex Hierarchy")

  
 **Figure 1 The hierarchy from templates to questions in RapidStart Services**

As the Designer for your organization in RapidStart Services, when you create a template, you can do the following:

  - Enter a name and a description.

  - Specify whether the template will be used to configure a business process or a module in Microsoft Dynamics AX.

  - Select the version of Microsoft Dynamics AX 2012 to which the template applies.

After you have provided this information, you can add functional areas to the template, which can be used when a new configuration project is created in the **Configure** area of RapidStart Services.


> [!NOTE]
> <P>The <STRONG>Configure</STRONG> area is used to create and manage configuration projects. It is also the area where business experts answer the questions to provide information that will help configure an implementation of RapidStart Services.</P>



When an administrator creates a new configuration project in the **Configure** area of RapidStart Services, they can choose whether to configure the project as a business process or a module. The administrator can also choose to create a custom template as they go. In that case, they do not select a template that you created in the **Design** area. Instead, they select any combination of functional areas to include in the custom template.


> [!IMPORTANT]
> <P>If you want to include the <STRONG>Base information</STRONG> functional area in a custom template that you create, you must add <STRONG>Base information</STRONG> as the first functional area in the template. Base information is used to define company-related information and fiscal calendar options. The questions in the <STRONG>Base information</STRONG> functional area must be answered before questions in any other functional area.</P>



## See also

[Learn about published and unpublished templates and functional areas in RapidStart Services](learn-about-published-and-unpublished-templates-and-functional-areas-in-rapidstart-services.md)

[Learn about functional areas in RapidStart Services](learn-about-functional-areas-in-rapidstart-services.md)

[Create a template in RapidStart Services](create-a-template-in-rapidstart-services.md)

[Copy a template in RapidStart Services](copy-a-template-in-rapidstart-services.md)

[Copy a template from another tenant in RapidStart Services](copy-a-template-from-another-tenant-in-rapidstart-services.md)

[Add sub-templates to a parent template in RapidStart Services](add-sub-templates-to-a-parent-template-in-rapidstart-services.md)

[Publish a template in RapidStart Services](publish-a-template-in-rapidstart-services.md)

[Unpublish a template in RapidStart Services](unpublish-a-template-in-rapidstart-services.md)

  


