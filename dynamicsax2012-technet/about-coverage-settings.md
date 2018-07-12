---
title: About coverage settings
TOCTitle: About coverage settings
ms:assetid: 9d1b8d56-c888-4dbe-9396-468cc6d0d720
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571706(v=AX.60)
ms:contentKeyID: 36931877
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About coverage settings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Master scheduling uses coverage settings to calculate item requirements.

You can specify coverage settings in several ways:

  - Specify coverage settings for a coverage group
    
    You can create a coverage group that contains settings for all products that are linked to the coverage group. Click **Master planning** \> **Setup** \> **Coverage** \> **Coverage groups**.
    
    You can link a coverage group to a product. Use the **Coverage group** field in the **Item coverage** form. If you do not link a coverage group to a product, the program uses the **General coverage group** that is specified in the **Master planning parameters** form as the default.

  - Specify coverage settings for a product
    
    You can create coverage settings for a specific product. Click **Inventory management** \> **Periodic** \> **Forecast** \> **Entry** \> **Items**. Select the product, on the **Action pane**, on the **Plan** tab, in the **Coverage** group, click **Item coverage** to open the **Item coverage** form.
    
    If the product is linked to a coverage group, you can override the coverage group settings by using the **Override** field.

  - Specify coverage settings for a product by using a wizard
    
    The wizard is a step-by-step guide to help you set up the primary item coverage parameters. In the **Item coverage** form, click **Wizard** to open the **Item Coverage Wizard**.

  - Specify coverage settings for a dimension group
    
    Click **Product information management** \> **Common** \> **Released products**. On the **Action pane**, on the **Product** tab, in the **Set up** group, click **Dimension groups**. Select the dimension group, and select the **Coverage plan by dimension** field to create the coverage settings for a product dimension group or a storage dimension group.

## See also

[Create a coverage group](create-a-coverage-group.md)

[Coverage groups (form)](https://technet.microsoft.com/en-us/library/aa552922\(v=ax.60\))

[Item coverage (form)](https://technet.microsoft.com/en-us/library/aa619147\(v=ax.60\))

  


