---
title: (POL) Set up excise taxes
TOCTitle: (POL) Set up excise taxes
ms:assetid: 2af7d491-dd89-4fbe-a9c0-fcc671576388
ms:mtpsurl: https://technet.microsoft.com/library/JJ678163(v=AX.60)
ms:contentKeyID: 49386886
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up excise taxes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can create sales orders or post invoices that include excise taxes, you must set up the following:

  - Create an excise tax ledger posting group.

  - Create a sales tax code for excise tax.

  - Add the sales tax code for excise tax to sales tax groups and item sales tax groups.

  - Enable excise tax posting to the ledger.

## Create excise tax ledger posting groups

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

2.  Click **New**.

3.  Enter a name and description for the ledger posting group.

4.  In the **Sales tax payable** field, select the excise tax main account.
    

    > [!NOTE]
    > <P>You must select a main account that has a posting type of <STRONG>Sales tax</STRONG>.</P>



## Create a sales tax code for excise tax

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New**.

3.  Enter a name and description for the sales tax code.

4.  Select **Excise** as the type of tax.

5.  Select the currency in which the sales tax is calculated.

6.  Select a sales tax settlement period.
    

    > [!NOTE]
    > <P>This is the period in which the selected sales tax, represented by the sales tax code, is calculated and paid.</P>



7.  In the **Ledger posting group** field, select the excise tax ledger posting group that you created in the previous procedure.

8.  Enter additional information about the sales tax code.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa553257(v=ax.60)">Sales tax codes (form)</A>.</P>



9.  Click **Values** to open the **Values** form, where you can specify a sales tax code value or percentage for the sales tax calculation of a selected sales tax code.

10. In the **Values** form, enter the excise duty percentage in the **Duty** field.

11. Close the **Values** form and the **Sales tax codes** form.

## Add the sales tax code for excise tax to sales tax groups and item sales tax groups

Transactions that are subject to sales taxes must be associated with both a sales tax group and an item sales tax group. Sales tax is calculated only for the sales tax codes that are included in both the sales tax group and the item sales tax group.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Add the sales tax code that you created in the previous procedure to sales tax groups. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

2.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Add the sales tax code that you created in the previous procedure to the item sales tax groups. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

## Enable excise tax posting to the ledger

When you enable excise tax posting, excise tax is posted to the ledger. If excise tax posting is not enabled, excise tax is calculated and is still displayed on the **List of excise tax transactions** report. However, excise tax is not posted to the ledger.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Ledger and sales tax**.

3.  Select the **Excise posting** check box.

  


