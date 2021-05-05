---
title: Add batch attribute values to an inventory batch
TOCTitle: Add batch attribute values to an inventory batch
ms:assetid: a9ea20f1-d0fc-4f61-af23-96472f96f9d0
ms:mtpsurl: https://technet.microsoft.com/library/Hh242690(v=AX.60)
ms:contentKeyID: 36058899
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add batch attribute values to an inventory batch 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add batch attribute values to an inventory batch after you have added the attributes to the item associated with the batch.

1.  Click **Inventory management** \> **Inquiries** \> **Dimensions** \> **Batches**.

2.  Select the inventory batch.

3.  Click **Inventory batch attributes**. The **Inventory batch attributes** form is displayed

4.  Add the batch attributes to the batch.
    
      - To add all batch attributes that have been defined for the item, click the **Load item attributes** button. The attributes are automatically loaded to the batch.
    
      - To add only certain batch attributes, for each attribute you want to add, press CTRL+N and select the attribute. Then enter the value for the attribute in the **Attribute value** field.
        

        > [!NOTE]
        > <P>For attributes that use <STRONG>Fraction</STRONG> and <STRONG>Integer</STRONG> attribute types, the value that you enter must be in the <STRONG>Minimum</STRONG> and <STRONG>Maximum</STRONG> range defined for the item on the <STRONG>Product specific</STRONG> form.</P>



## See also

[About batch attributes](about-batch-attributes.md)

[(PM) Batches (form)](https://technet.microsoft.com/library/hh209252\(v=ax.60\))

[Inventory batch attributes (form)](https://technet.microsoft.com/library/hh209284\(v=ax.60\))

[Product specific (form)](https://technet.microsoft.com/library/hh227369\(v=ax.60\))

  


