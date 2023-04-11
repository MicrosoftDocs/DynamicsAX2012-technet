---
title: (LVA) Create an inventory counting list
TOCTitle: (LVA) Create an inventory counting list
ms:assetid: 8aa00731-53e1-48a8-86c2-d16c69e6abe2
ms:mtpsurl: https://technet.microsoft.com/library/JJ721424(v=AX.60)
ms:contentKeyID: 49729991
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Latvia
---

# (LVA) Create an inventory counting list 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you create counting journals for items, you can print the inventory counting list for the transactions.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Journals** \> **Item counting** \> **Counting**.

2.  Press CTRL+N to create a new inventory journal, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Inventory journal (form)" in the Applications and Business Processes Help.</P>



3.  Click **Lines** to open the **Journal lines, Inventory** form.

4.  Press CTRL+N to create a line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Journal lines, Inventory count (form)" in the Applications and Business Processes Help.</P>



5.  In the **Date** field, select the date that the physical adjustment will be made.

6.  In the **Item number** field, select the item number of the inventory item to be posted.

7.  In the **Warehouse** field, select the warehouse where the items will be stored.

8.  In the **Quantity** field, enter the quantity of the item you want to adjust.

9.  Click **Validate** to validate the journal lines transaction.

10. Click **Post** to check for errors, and then post the journal line transactions.
    

    > [!NOTE]
    > <P>You can view a journal of the item counts that have already been made in the <STRONG>Counting history</STRONG> form. For more information, see "Counting journal (form)" in the Applications and Business Processes Help.</P>



11. In the **Inventory journal** form, click **Print** \> **Counting list** to open the **Counting list** report.
    

    > [!NOTE]
    > <P>The following fields are available only when you select the second <STRONG>Counting list</STRONG> menu item.</P>



12. Select the **Print on-hand** check box to print the on-hand quantities.

13. Select the **Skip zero** check box to skip items with zero quantities.

14. Click **Setup** to open the **Counting list - Report** form and set up the selection criteria.

15. Click **OK** to print the **Counting list** report.

  


