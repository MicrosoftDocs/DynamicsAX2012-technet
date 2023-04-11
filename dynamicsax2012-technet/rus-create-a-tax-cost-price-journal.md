---
title: (RUS) Create a tax cost price journal
TOCTitle: (RUS) Create a tax cost price journal
ms:assetid: 85f4fc5f-39c0-41a5-84b1-ebd759514232
ms:mtpsurl: https://technet.microsoft.com/library/JJ923553(v=AX.60)
ms:contentKeyID: 52075401
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a tax cost price journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a tax cost price journal for work in process (WIP) and finished products (FP), such as items that are in production, half-finished items, finished items in inventory, and shipped items.

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  In the **Tax register journal** form, click **Ledger journal** \> **Tax cost price** to create the **Tax cost price** journal.

3.  Click **Create** \> **Create journal** to open the **Tax cost price** form. Then create a tax cost price journal for the period of the WIP and FP estimation in tax accounting register calculation.

4.  Click **Lines** to open the **Journal voucher** form. Journal lines are created automatically.

5.  In the **Date** field, modify the end date for the period during which the register is calculated.

6.  In the **Account type** field, select the **Ledger** account type.

7.  In the **Account** field, select the account number.

8.  On the **General** tab, in the **Offset account** field group, in the **Offset account type** field, view the **Ledger** offset account type.

9.  In the **Offset account** field, select the offset account number.

10. In the **Offset-transaction text** field, select a description for the transaction.
    

    > [!NOTE]
    > <P>The transactions amount on accrual and write-off is determined from the register values in the <STRONG>Accrued accounting</STRONG>, <STRONG>Accrued TA</STRONG> and <STRONG>Written off accounting</STRONG>, or <STRONG>Written off TA</STRONG> columns.</P>



11. Click the **Financial dimensions** button to modify the financial dimensions codes for the journal line.

12. Click **Validate** \> **Validate** to validate the journal.

13. Click **Post** \> **Post** to post the tax cost price journal. The journal turnovers are created for production and sales tax accounts.
    

    > [!NOTE]
    > <P>To create a storno transaction for the tax cost journal, in the <STRONG>Tax cost price</STRONG> form, click <STRONG>Create</STRONG> &gt; <STRONG>Reverse journal</STRONG>. The journal is reversed, and the journal type field is updated with the <STRONG>Reversing entry</STRONG> journal type. The <STRONG>Reversed</STRONG> check box becomes available. You must refer to the turnover of sales tax accounts when you set up the profit tax declaration in the Financial reports generator.</P>



## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/library/jj856114\(v=ax.60\))

  


