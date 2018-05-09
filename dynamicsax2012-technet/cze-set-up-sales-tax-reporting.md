---
title: (CZE) Set up sales tax reporting
TOCTitle: (CZE) Set up sales tax reporting
ms:assetid: cc110308-4654-48bb-9c14-b5ff3adf1e0e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856967(v=AX.60)
ms:contentKeyID: 50411972
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Set up sales tax reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you report sales tax transactions for your organization, you can set up the report structure in an XML format. You can modify the XML format for your location. When you export sales tax information and create the sales tax report, you can send the XML file to sales tax authorities.

**Prerequisites**

  - Define parameters to use to calculate sales taxes. For example, define how to calculate tax on cash discounts, overpayments, and corrections. For more information, see [General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\)).

  - Set up sales tax codes to use to calculate the taxes and duties that your organization is obligated to collect from customers and pay to tax authorities. For more information, see [Create various kinds of sales tax codes](create-various-kinds-of-sales-tax-codes.md) and [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

## Set up XML elements for sales tax report lines

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Sales tax reporting XML codes**.

2.  In the **Sales tax reporting XML codes** form, in the **XML element name** field, enter a unique name for the XML element.

3.  Optional: Add a description of the XML element.

4.  If the XML element is a child element of another element, in the **Parent element** field, enter the name of the parent element.

5.  In the **XML attribute name** field, enter an attribute for the selected XML element.

6.  To define default values for the XML elements, click **Initialize**. The default values are displayed in the **Sales tax reporting XML codes** form.

## Set up sales tax report lines

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Sales tax reporting codes**.

2.  In the **Sales tax reporting codes** form, in the **Report layout** field, enter a name for the sales tax report.

3.  In the **Reporting code** field, enter a number that corresponds to a box number in the sales tax form for your country or region.

4.  Optional: In the **Total calculation** field group, select one or more report lines to include on a total line on the sales tax report.

5.  Enter the remaining information for the report lines and total calculation lines. For more information, see [(CZE) Sales tax reporting codes (modified form)](https://technet.microsoft.com/en-us/library/jj910971\(v=ax.60\)).

## Assign sales tax codes to report lines

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  In the **Sales tax codes** form, on the **Report setup** FastTab, in the **Sales tax payable** field, select a reporting code for sales taxes that are due to the tax authorities. The reporting code corresponds to a box number on the sales tax form for your country or region.

3.  In the **Sales tax receivable** field, select a reporting code for sales tax refunds, if any, that offset sales taxes that are due.

## See also

[Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

