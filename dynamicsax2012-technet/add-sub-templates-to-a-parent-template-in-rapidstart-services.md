---
title: Add sub-templates to a parent template in RapidStart Services
TOCTitle: Add sub-templates to a parent template in RapidStart Services
ms:assetid: b64f5d25-8e7e-4476-b102-832abbd10218
ms:mtpsurl: https://technet.microsoft.com/library/Hh413248(v=AX.60)
ms:contentKeyID: 36918939
author: Khairunj
ms.author: daxcpft
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- sub-template
- parent template
---

# Add sub-templates to a parent template in RapidStart Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

To create a more complex template for your Microsoft Dynamics ERP configuration in Microsoft Dynamics ERP RapidStart Services, you can create sub-templates and add them to a parent template. You can also add sub-templates to an existing sub-template. To serve as a parent template, a template or sub-template must have no functional areas assigned to it.

1.  In the RapidStart Services header, click **Design**.

2.  Click the **Template** button, and then click **New sub-template**.

3.  In the **Sub-template** form, select the **Sub-template** check box.

4.  In the **Parent template** field, select the template to which you want to add this sub-template.

5.  Enter a name for the sub-template in the **Name** field.

6.  Optional: In the **Description** field, describe the purpose of this template and how it will be used.
    

    > [!NOTE]
    > <P>The sub-template inherits the template type and release version from the parent template.</P>



7.  Click **Create**.

You can now add functional areas or sub-templates at an additional child level to the sub-template.

## See also

[Create a template in RapidStart Services](create-a-template-in-rapidstart-services.md)

[Publish a template in RapidStart Services](publish-a-template-in-rapidstart-services.md)

[Add a functional area to a template in RapidStart Services](add-a-functional-area-to-a-template-in-rapidstart-services.md)

  


