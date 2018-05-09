---
title: (IND) Tax information in intercompany transactions
TOCTitle: (IND) Tax information in intercompany transactions
ms:assetid: df365d86-4c35-47cf-b0fb-aac9027b1321
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710896(v=AX.60)
ms:contentKeyID: 49386306
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Tax information in intercompany transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Intercompany transactions are based on the standard purchase order and sales order functionality. However, there are some differences when sales tax is calculated in intercompany transactions:

  - You must enter the basic setup information to calculate the sales tax for purchase or sales transactions for both the companies.


> [!NOTE]
> <P>For more information, see <A href="ind-set-up-sales-taxes-for-multiple-taxation-transactions.md">(IND) Set up sales taxes for multiple taxation transactions</A>.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



  - The default tax information details of the intercompany order are from the company information, based on the address of the company. The tax information of the company in a corresponding sales order or purchase order is independent, and changes will not affect the corresponding order. However, you must manually make changes to the tax information of an intercompany order.

For example, IC 1 and IC 2 are two companies that are created for intercompany transactions. You create a sales order for IC 1 and select the tax information for IC 1 on the **Tax information** tab in the **Sales order** form. When the sales order is posted, a corresponding purchase order is created in IC 2. The tax information about IC 2 is automatically displayed on the **Tax information** tab in the **Purchase order** form for IC 2.


> [!NOTE]
> <P>You can change the tax information details when the transaction order is created to automatically create intercompany orders. The changes that are made in the tax information in either of the companies will not affect the transaction. However, the changes must be made manually.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

