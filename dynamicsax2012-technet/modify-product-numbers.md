---
title: Modify product numbers
TOCTitle: Modify product numbers
ms:assetid: e832e5fc-bfb5-4680-81dc-a79452de971e
ms:mtpsurl: https://technet.microsoft.com/library/Aa573197(v=AX.60)
ms:contentKeyID: 39519352
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Modify product numbers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.

2.  On the **Action Pane**, in the **Maintain** group, click **Edit** to open the **Product details** form.

3.  On the **Action Pane**, in the **Maintain** group, click **Rename**.

4.  In the **New product number** field, enter the new product number.

5.  If you want to modify the numbers for product variants, select **Apply change to product variants**.
    

    > [!NOTE]
    > <P>The numbers of product variants are derived from the number of the product master. If you select this check box, and the number of the product master is changed, the numbers of the product variants reflect this change. This check box is only available for product masters.</P>



6.  Click **OK**.
    

    > [!NOTE]
    > <P>When you click <STRONG>OK</STRONG>, you start a job that finds all occurrences of the old product number and replaces them with the new number. The time that is required to run this job depends on the amount of data that must be handled.</P>


  


