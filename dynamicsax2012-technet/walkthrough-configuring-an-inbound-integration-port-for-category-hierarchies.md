---
title: 'Walkthrough: Configuring an inbound integration port for category hierarchies'
TOCTitle: 'Walkthrough: Configuring an inbound integration port for category hierarchies'
ms:assetid: 763d4fcf-46a4-4487-b409-963c2eadeed4
ms:mtpsurl: https://technet.microsoft.com/library/Dn454569(v=AX.60)
ms:contentKeyID: 57085674
author: Khairunj
ms.date: 09/24/2013
mtps_version: v=AX.60
f1_keywords:
- walkthrough
- category
- categories
- data import
- commodity code
- Category hierarchy
- import category
---

# Walkthrough: Configuring an inbound integration port for category hierarchies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about how to configure an integration port in Microsoft Dynamics AX 2012 to import commodity codes into a category hierarchy. This task is one step in the process of enabling you to import commodity codes into AX 2012. For more information about how to import commodity codes, see [Microsoft Dynamics AX 2012 White Paper: Import Commodity Codes to a Category Hierarchy](https://go.microsoft.com/fwlink/?linkid=313695).

In AX 2012, you can use category hierarchies to classify products and transactions for reporting and analysis. Several industry and regulatory classification systems are available for your organization to use. For more information, see [About category hierarchies](about-category-hierarchies.md).

You import commodity codes from an industry or other external classification system by using an XML file format. Before you can import commodity codes, you must set up an integration port by using Microsoft Dynamics AX Application Integration Framework (AIF). Only users who are assigned to the System Administrator role in AX 2012 can configure integration ports.

## Initialize AIF

If this is the first time that you have worked with services and AIF, you must set up AIF. To set up AIF, follow these steps:

1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.

2.  Expand the **Initialize system** node.

3.  Click **Set up Application Integration Framework**.

This operation registers adapters, basic ports, and services. The operation can take some time to be completed.

## Create the integration port

Use this procedure to set up the inbound port and to specify the location of the commodity codes file that you want to import. You must also associate the inbound port with a service operation so that imported information can be processed.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  In the **Inbound ports** form, click **New**.

3.  Enter a name and an optional description to identify the port that is used to import commodity codes.

4.  In the **Adapter** list, select **File system adapter**.

5.  In the **URI** field, enter the path of the root folder where the commodity codes file is stored.

6.  On the **Service contract customizations** FastTab, click **Service operations**.

7.  In the **Select service operations** form, in the **Remaining service operations** pane, select the **EcoRecCategoryImport.create** service operation, and then click the **\<** button to move the service operation to the **Selected service operations** pane.
    
    If the **EcoRecCategoryImport.create** service operation isn’t listed in the **Select service operations** form, you must register it. Complete the following steps to register the service:
    
    1.  Open the AOT, and then click **Services**.
    
    2.  Right-click **EcoResCategoryImportService**, and then click **Add-ins** \> **Register service**.
    
    3.  Close the AOT.
    
    4.  Refresh the **Select service operations** form. You can press **F5** or click **File** \> **Refresh**. You can also refresh the form by closing it and reopening it.
    
    5.  Move the **EcoResCategoryImportService** service operation to the **Selected service operations** pane.

8.  Optional: In the **Inbound ports** form, select security and troubleshooting settings for the inbound port. For more information about these settings, see [AIF inbound ports (form)](https://technet.microsoft.com/library/hh208821\(v=ax.60\)).

9.  Click **Activate**.

## See also

[Managing integration ports](managing-integration-ports.md)

