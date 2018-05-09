---
title: (RUS) Set up a dual warehouse layer
TOCTitle: (RUS) Set up a dual warehouse layer
ms:assetid: e764ee10-064b-4821-be17-40154fa6924b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733298(v=AX.60)
ms:contentKeyID: 49685265
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- dual
- warehouse
- layer
- (RUS)
- Russia
---

# (RUS) Set up a dual warehouse layer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can perform cost value accounting by using a reporting currency. You can also perform recalculations or inventory closings, or adjust on-hand inventory or inventory receipts in the reporting currency to generate ledger transactions. These ledger transactions use the dual warehouse posting layer.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  Click **Number sequences**, and then in the **Number sequences** area, set up the number sequence that is used to number the following transactions:
    
      - Inventory closings
    
      - Inventory recalculation in a reporting currency
    
      - Ledger transactions that are created during inventory recalculation
    
      - Inventory closings in a reporting currency
    
      - Inventory transaction adjustments in a reporting currency
    
      - Ledger transactions that are created when cost price adjustments are performed
    
      - Settlement transactions

3.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Item model groups**.

4.  Select the **Post secondary financial** check box to use the settings to post inventory transactions in a reporting currency to the dual warehouse posting layer.

5.  Close the form.

6.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.

7.  On the **Inventory** tab, select **Loss** or **Profit** to set up ledger accounts that are used to post adjustments to inventory receipts and on-hand inventory balance adjustments. You can select **Rounding - Loss** and **Rounding - Profit** to set up ledger accounts that are used to post rounded amounts that result from inventory recalculations or closings.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

