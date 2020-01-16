---
title: (HUN) Create and post a sales order invoice with a specific VAT register date
TOCTitle: (HUN) Create and post a sales order invoice with a specific VAT register date
ms:assetid: f558e197-5836-4c0b-ad88-f431941311ec
ms:mtpsurl: https://technet.microsoft.com/library/JJ664416(v=AX.60)
ms:contentKeyID: 49385504
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer invoice
- VAT register date
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create and post a sales order invoice with a specific VAT register date 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you post a sale invoice, you can select the date on which to report value-added tax (VAT). Use this procedure to create and post an invoice that has a specific VAT register date.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

2.  In the **Create sales order** form, enter the required information, and then click **OK.**

3.  In the **Sales order** form, enter the sales order lines. For more information, see [Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\)).

4.  On the **Action Pane**, on the **Sell** tab, in the **Generate** group, click **Sales order confirmation**.

5.  After you ship the items, in the **Sales order** form, on the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

6.  In the **Posting invoice** form, on the **Setup** tab, in the **Date of VAT register** field, select the transaction date for the VAT register.

7.  Enter any additional information, and then click **OK**.

When you post an invoice that includes outgoing tax that will be posted on a future date, the amount of VAT is posted to a temporary account. Later, on the date that you selected, it is posted to the VAT account.

  


