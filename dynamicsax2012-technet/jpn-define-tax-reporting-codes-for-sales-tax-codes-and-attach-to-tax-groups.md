---
title: (JPN) Define tax reporting codes for sales tax codes and attach to tax groups
TOCTitle: (JPN) Define tax reporting codes for sales tax codes and attach to tax groups
ms:assetid: 1c11d9d8-c9fd-44d7-8f5c-d55e7f9f0a69
ms:mtpsurl: https://technet.microsoft.com/library/JJ711017(v=AX.60)
ms:contentKeyID: 49386426
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Define tax reporting codes for sales tax codes and attach to tax groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**.

2.  Press CTRL+N to create a new sales tax code.

3.  Click the **Report setup** tab. Select the sales tax reporting codes in the required fields.

4.  Click the **Report setup – credit note** tab and select the sales tax reporting codes in the required fields.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa553257(v=ax.60)">Sales tax codes (form)</A> and <A href="create-various-kinds-of-sales-tax-codes.md">Create various kinds of sales tax codes</A>.</P>



5.  Press CTRL+S or close the form.

6.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Attach the sales tax codes set up in steps 1 to 5 to the tax groups.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa498345(v=ax.60)">Sales tax groups (form)</A> and <A href="set-up-and-use-a-sales-tax-group.md">Set up and use a sales tax group</A>.</P>



7.  Press CTRL+S or close the form.

8.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Attach the sales tax codes that were set up in steps 1 to 5 to the tax groups.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa615960(v=ax.60)">Item sales tax groups (form)</A>.</P>



9.  Press CTRL+S or close the form.

## Post transactions using tax groups

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Press CTRL+N to create a purchase order or sales order and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="create-a-purchase-order.md">Create a purchase order</A>.</P>



3.  In the lower pane, click the **Setup** tab and select the sales tax group and item sales tax group in the **Sales tax group**. field.

4.  In the upper pane, click **Posting** \> **Invoice** to post the invoice.

  


