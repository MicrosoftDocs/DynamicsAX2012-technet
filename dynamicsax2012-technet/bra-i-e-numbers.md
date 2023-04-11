---
title: (BRA) I.E. Numbers
TOCTitle: (BRA) I.E. Numbers
ms:assetid: c91972d1-3143-4eb9-8612-cb35a5d6ba0d
ms:mtpsurl: https://technet.microsoft.com/library/JJ714200(v=AX.60)
ms:contentKeyID: 49651309
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) I.E. Numbers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

IE numbers, or state registration numbers, are required for each customer and vendor record. When you upgrade to Microsoft Dynamics AX 2012 R2 or R3, you can update any invalid IE numbers that have been entered for customers and vendors.

You are not required to update the invalid IE numbers before you complete the upgrade to Microsoft Dynamics AX 2012 R2 or R3. However, you will not be able to generate or receive fiscal documents that contain an invalid IE number. You can update invalid IE numbers for customers and vendors at any time.

The **Party upgrade – Invalid I.E. number** form provides a list of all customer and vendor records that have an invalid IE number. This list is generated automatically and provided during upgrade preprocessing. The following steps describe how to update IE numbers.

1.  On the **Preprocessing upgrade checklist**, click the **I.E. numbers** task to open the **Party upgrade – Invalid I.E. number** form.

2.  In the **Party upgrade – Invalid I.E. number** form, select the record that you want to update and click **Fix**.
    
    Depending on the record type that you select, the **Customers** or **Vendors** form will open.

3.  On the **Fiscal information** tab, in the **IE** field, enter a valid IE number for the party record and then close the form.

4.  Repeat steps 2 and 3 until you have made all of the necessary updates to the records that contain invalid IE numbers.
    
    Click **Refresh** to see an updated list of records that contain invalid IE numbers.

5.  When you have made all of the necessary updates, click **Set to ready for upgrade**.

  


