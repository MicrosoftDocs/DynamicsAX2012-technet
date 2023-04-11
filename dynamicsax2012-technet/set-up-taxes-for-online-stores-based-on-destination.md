---
title: Set up taxes for online stores based on destination
TOCTitle: Set up taxes for online stores based on destination
ms:assetid: 4aa0743c-6446-42e8-b4e9-8aa6c49de9f1
ms:mtpsurl: https://technet.microsoft.com/library/JJ728685(v=AX.60)
ms:contentKeyID: 49556590
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up taxes for online stores based on destination 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you set up taxes for an online store, you can set up sales tax groups for specific geographic areas. In this way, the customer's shipping address can be automatically mapped to the correct sales tax groups when the customer shops in your online store. Some tax laws require that taxes must be collected based on the delivery address of the sales order.

This setup can be especially useful if you do not use an independent tax service to provide sales tax rates. It can also help ensure a good shopping experience for regular or especially important customers.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  On the left side of the form, select a sales tax group, and then, on the **Destination based tax** FastTab, click **Add**.

3.  Starting with the **Country/region** field, select options in the following fields to add a geographic area to the sales tax group:
    
      - **Country/region**
    
      - **State**
    
      - **County**
    
      - **City**
    
      - **District**
    
      - **ZIP/postal code**
    
    For example, to add a county to a sales tax group, select a country or region, select a state, and then select the county.

## See also

[About setting up taxes](about-setting-up-taxes.md)

  


