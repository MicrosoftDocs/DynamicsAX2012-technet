---
title: About setting up taxes
TOCTitle: About setting up taxes
ms:assetid: b8af4de8-1aae-44b4-8f69-7bb1596c5f61
ms:mtpsurl: https://technet.microsoft.com/library/Hh597220(v=AX.60)
ms:contentKeyID: 39519292
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- tax
- taxes
audience: Application User
ms.search.region: Global
---

# About setting up taxes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You must set up sales tax codes, item sales tax groups, and sales tax groups by completing the tasks that are described in Microsoft Dynamics AX Help. To support retail operations, you must also complete the following tasks.

  - Required: [Assign sales tax groups to stores](assign-sales-tax-groups-to-stores.md)

  - Required: [Specify inclusive or exclusive tax](specify-inclusive-or-exclusive-tax.md)

  - Optional: [Set up sales tax overrides](set-up-sales-tax-overrides.md)

  - Optional: [Set other tax options for stores](set-other-tax-options-for-stores.md)

In Microsoft Dynamics AX, two types of tax groups are used. Sales tax groups are assigned to customers, and item sales tax groups are assigned to products. For each product that is sold, Microsoft Dynamics AX calculates tax by determining the sales tax codes that apply to both the product and the customer to whom the product is sold. If a tax group is not assigned to either the product or the customer, no tax is applied.

In Retail, sales tax groups must be assigned to stores. For each product that is sold, Retail calculates tax by determining the sales tax codes that apply to both the product and the store where the product is sold. If an item sales tax group is not assigned to the product, no tax is applied.

Retail calculates taxes for return transactions by using the schedules for sales tax rates that are assigned to each sales tax code. Set up these schedules to guarantee that you do not refund more tax than you collected.


> [!NOTE]
> <UL>
> <LI>
> <P>Microsoft Dynamics AX for Retail POS uses only tax settings that are related to retail tax calculation.</P>
> <LI>
> <P>If a customer is added to the transaction, the sales tax group for the customer is used in tax calculations only if the tax options for the store require that the sales tax group be used. For more information, see <A href="set-other-tax-options-for-stores.md">Set other tax options for stores</A>.</P>
> <LI>
> <P>Retail POS does not support the <STRONG>Check sales tax groups</STRONG> option in the <STRONG>General ledger parameters</STRONG> form.</P></LI></UL>


  


