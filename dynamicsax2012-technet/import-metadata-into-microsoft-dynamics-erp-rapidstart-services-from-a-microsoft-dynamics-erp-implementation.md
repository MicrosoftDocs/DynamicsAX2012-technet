---
title: Import metadata into Microsoft Dynamics ERP RapidStart Services from a Microsoft Dynamics ERP implementation
TOCTitle: Import metadata into Microsoft Dynamics ERP RapidStart Services from a Microsoft Dynamics ERP implementation
ms:assetid: 1e45e047-158d-4318-9cf4-f4395735a91c
ms:mtpsurl: https://technet.microsoft.com/library/Hh413225(v=AX.60)
ms:contentKeyID: 36918916
author: tonyafehr
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- ERP
- import metadata
- metatdata
---

# Import metadata into Microsoft Dynamics ERP RapidStart Services from a Microsoft Dynamics ERP implementation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

When the Designer for your organization creates new questions in Microsoft Dynamics ERP RapidStart Services, he or she has access to all the metadata that is available in all versions of Microsoft Dynamics AX 2012. This metadata includes the names of fields, tables, enums, services, classes, and methods from Microsoft Dynamics AX 2012.

The Designer can also create questions that are used to configure values in Microsoft Dynamics AX for solutions that are developed by partners or independent software vendors (ISVs). However, in this case, you as the Customer administrator must first import the required metadata into RapidStart Services from the target implementation of Microsoft Dynamics AX 2012. The Designer can then use the fields, tables, enums, services, classes, and methods from those solutions when he or she creates questions in the **Design** area of RapidStart Services.

1.  In the RapidStart Services header, click **Administer**, and then, in the left pane, click **Import metadata**.

2.  Click the **Import metadata** button.

3.  In the **Import metadata** form, in the **Endpoint** field, select the name of the Microsoft Dynamics AX 2012 implementation from which to import metadata.

4.  In the **Release version** field, select or verify the version of Microsoft Dynamics AX from which to import metadata.

5.  If you want to import metadata for a specific language that is installed in the Microsoft Dynamics AX implementation, in the **Language** field, select or verify the language.

6.  If you want to refresh metadata only for Application Integration Framework (AIF) services and exclude other types of metadata from the import, select the **Service metadata only** check box.

7.  Click **OK**.

## See also

[Learn about extending the capabilities of Microsoft Dynamics ERP RapidStart Services](learn-about-extending-the-capabilities-of-microsoft-dynamics-erp-rapidstart-services.md)

  


