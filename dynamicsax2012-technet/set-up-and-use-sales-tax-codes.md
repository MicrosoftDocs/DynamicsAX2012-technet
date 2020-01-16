---
title: Set up and use sales tax codes
TOCTitle: Set up and use sales tax codes
ms:assetid: 188be966-db4f-49dc-98a7-6d72128415b1
ms:mtpsurl: https://technet.microsoft.com/library/Aa569910(v=AX.60)
ms:contentKeyID: 36056100
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up and use sales tax codes
audience: Application User
ms.search.region: Global
---

# Set up and use sales tax codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Transactions that are subject to sales taxes must be associated with both a sales tax group and an item sales tax group. Sales tax is calculated only for the sales tax codes that are included in both the sales tax group and the item sales tax group.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create sales tax codes. For more information, see [Create various kinds of sales tax codes](create-various-kinds-of-sales-tax-codes.md).

3.  Optional: If your legal entity operates in the United States, you can set up sales tax jurisdictions in addition to sales tax codes, and attach sales tax jurisdictions to sales tax groups. Sales tax codes are attached to the sales tax group through the sales tax jurisdictions.

4.  Optional: If you will receive sales tax information through a web service, map the sales tax codes that are used by vendors to the sales tax codes in Microsoft Dynamics AX. For more information, see [Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\)).

5.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Add sales tax codes to the sales tax groups. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

6.  Add sales tax groups to each customer and vendor account, and to main accounts to which purchase or sales transactions that do not involve a customer or vendor account are posted. For more information, see [Set up a default tax profile for a customer or vendor](set-up-a-default-tax-profile-for-a-customer-or-vendor.md).

7.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Add sales tax codes to the item sales tax groups. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

8.  Add default item sales tax groups to items and ledger accounts:
    
      - Add a default item sales tax group for purchase orders and sales order to each item. For more information, see [Set up default item sales tax groups for an item](set-up-default-item-sales-tax-groups-for-an-item.md).
    
      - Add a default item sales tax group to the ledger accounts to which purchase or sales transactions that do not involve inventory items are posted. For more information, see [Set up a default item sales tax group for a main account](set-up-a-default-item-sales-tax-group-for-a-main-account.md).
    
    An appropriate item sales tax code is then proposed as the default sales tax code on all sales order, purchase order, and journal lines when you enter the item or the ledger account.

## Example: Calculate sales tax

You prepare a sales order to customer ABC for item BATTERY and item WIDGET.

  - Customer ABC uses sales tax group STX, which includes sales tax codes VAT, BAT, ALC, and CHO.

  - Item BATTERY uses item sales tax group BAT, which includes sales tax codes VAT, EU25, and BAT.

  - Item WIDGET uses item sales tax group ALC, which includes sales tax codes VAT, EU25, and ALC.

The sales tax is calculated for each item line based on the sales tax codes that are added to sales tax group STX (selected for the customer account) and the item sales tax groups that apply to each item:

  - The sales tax for the BATTERY transaction is calculated according to sales tax codes VAT and BAT.

  - The sales tax for the WIDGET transaction is calculated according to sales tax codes VAT and ALC.

  


