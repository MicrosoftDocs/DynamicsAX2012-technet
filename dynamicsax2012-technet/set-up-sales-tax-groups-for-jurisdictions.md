---
title: Set up sales tax groups for jurisdictions
TOCTitle: Set up sales tax groups for jurisdictions
ms:assetid: d15ceae1-662d-4336-b70d-c94cfb43a22f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551024(v=AX.60)
ms:contentKeyID: 36059496
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax groups
- sales tax jurisdictions
audience: Application User
ms.search.region: Global
---

# Set up sales tax groups for jurisdictions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following steps describe how to set up sales tax groups for sales tax jurisdictions.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax jurisdictions**.

2.  Set up the sales tax jurisdictions that apply to the geographical area in which your organization is liable for sales taxes. This includes assigning appropriate sales tax codes to each sales tax jurisdiction. For more information, see [Set up sales tax jurisdictions](set-up-sales-tax-jurisdictions.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

4.  In the **Sales tax group setup** field, select **Sales tax jurisdictions** and press CTRL+S.

5.  In the **Rounding by** field, select the rounding convention for the sales tax group.
    

    > [!NOTE]
    > <P>For more information about this field and the other fields in the <STRONG>Sales tax groups</STRONG> form, see <A href="https://technet.microsoft.com/en-us/library/aa498345(v=ax.60)">Sales tax groups (form)</A>.</P>



6.  In the **Print** field, select how to print sales taxes on the invoice.

7.  On the **Jurisdiction setup** FastTab, select the sales tax jurisdictions that apply to the sales tax group. Enter information about the tax-exempt status and use tax, if applicable. The sales tax codes that are attached to a selected sales tax jurisdiction are displayed on the **Setup** FastTab.

8.  If necessary, you can change the sales tax codes of the jurisdiction in the **Sales tax jurisdictions** form.

When a journal line, purchase order line, or sales order line is created, the sales tax codes on the sales tax jurisdictions that are attached to sales tax groups are matched to the sales tax codes on the item sales tax groups. Sales taxes then are calculated for the transaction.

## See also

[Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md)

[Set up sales tax for the United States](set-up-sales-tax-for-the-united-states.md)

  


