---
title: (EEUR) Set up retail parameters for cash operations
TOCTitle: (EEUR) Set up retail parameters for cash operations
ms:assetid: e2aa7d20-d5a3-4574-a383-06eeb51b2c2a
ms:mtpsurl: https://technet.microsoft.com/library/Dn313048(v=AX.60)
ms:contentKeyID: 54936295
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailParameters
- RU - 00005
- RU – 00037
- MsDynAx060.Forms.RetailParameters
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Set up retail parameters for cash operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up parameters to create and post cash transactions in Retail. You can use cash payment journals, customer payment journals, or general journals to post sales transactions and payment transactions in the Retail POS. You can aggregate transactions that have the same properties when you post a statement. For more information, see [(EEUR) Set up for cash management for Retail POS](eeur-set-up-for-cash-management-for-retail-pos.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 1 for AX 2012 R2.</P>



1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**. In the left pane click, **Posting**

2.  In the **Posting** area, on the **Aggregation** FastTab, select the **Tender remove/float** check box to aggregate the remove tender transactions or float entry transactions that are associated with a statement line when you post the statement. A remove tender transaction is created when you withdraw cash from the POS cash drawer. A float entry transaction is created when you deposit cash in the POS cash drawer.

3.  Select the individual check boxes listed below to aggregate the transactions that are associated with a statement line when you post the statement:
    
      - **Bank drop** – Aggregate bank transactions
    
      - **Safe drop** – Aggregate safe transactions
    
      - **Income/Expense transactions** – Aggregate income transactions or expense transactions
    
      - **Voucher transactions** – Aggregate voucher transactions
    
      - **Customer payments** – Aggregate customer payments
    
      - **Sales and returns** – Aggregate sales and returns transactions

4.  On the **Payments** FastTab, select one of the following options:
    
      - **General journal** – This journal is used to post transactions other than cash payments and customer payments.
    
      - **Cash payment journal** – This journal is used to post cash payments.
    
      - **Customer payment journal** – This journal is used to post customer payments.

  


