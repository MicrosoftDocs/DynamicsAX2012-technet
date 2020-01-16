---
title: (LTU) Set up sales tax reporting
TOCTitle: (LTU) Set up sales tax reporting
ms:assetid: 957a798a-8a83-48da-868b-cae9a7b837af
ms:mtpsurl: https://technet.microsoft.com/library/Dn528957(v=AX.60)
ms:contentKeyID: 59641346
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Set up sales tax reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In Microsoft Dynamics AX, you can set up a report format that complies with the local tax report format for sales tax transactions. You can define how the transactions are summarized in the report by adding total lines and subtotal lines. You can also specify that a total or subtotal in the report in Microsoft Dynamics AX corresponds to a box number in the sales tax form for your country or region.

Before you report sales tax transactions for your organization, you can set up the report structure in an XML format. You can modify the XML format for your location. When you export sales tax information and create the sales tax report, you can send the XML file to sales tax authorities.

**Prerequisites**

  - Define parameters to use to calculate sales taxes. For example, define how to calculate tax on invoices, cash discounts, overpayments, and corrections. For more information, see [General ledger parameters (form)](https://technet.microsoft.com/library/aa557286\(v=ax.60\)).

  - Set up a tax authority to whom the taxes are paid. Also, select a report layout or structure for reporting taxes to the tax authority. For more information, see [Set up sales tax authorities](set-up-sales-tax-authorities.md).

  - Set up sales tax codes to use to calculate the taxes and duties that your organization is obligated to collect from customers and pay to tax authorities. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

## Set up XML elements for sales tax report lines

Create XML codes, which are also known as elements, that define the lines that you want to use to summarize transactions. You can define the lines in the XML format for your country/region by grouping child elements in a parent element.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Sales tax reporting XML codes**.

2.  To define default values for the XML elements, in the **Sales tax reporting XML codes** form, click **Initialize**. The default values are displayed in the form.

3.  To create a new XML element, click **New**. In the **XML element name** field, enter a unique name for the XML element.

4.  Optional: Add a description of the XML element.

5.  If the XML element is a child element of another element, in the **Parent element** field, enter the name of the parent element.

6.  In the **XML attribute name** field, enter an attribute for the selected XML element. For example, create an XML element to report sales that contain no VAT. Next, create an XML attribute **Non-taxable** for the XML element. When you generate the report, the attribute helps you identify the transactions that are included in the report line.

## Set up sales tax report lines

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Sales tax reporting codes**.

2.  In the **Sales tax reporting codes** form, in the **Report layout** field, enter a name for the sales tax report.
    

    > [!IMPORTANT]
    > <P>The report layout that you select must be the same layout that you select in the <STRONG>Sales tax authorities</STRONG> form on the <STRONG>General</STRONG> FastTab.</P>



3.  In the **Reporting code** field, enter a number that corresponds to a box number in the sales tax form for your country or region.

4.  Optional: In the **Total calculation** field group, select one or more report lines to include on a total line on the sales tax report.

5.  Enter the remaining information for the report lines and total calculation lines. For more information, see [(LTU) Sales tax reporting codes (modified form)](https://technet.microsoft.com/library/dn133215\(v=ax.60\)).

6.  To view and print a report for sales tax reporting codes, click **Sales tax reporting codes**.

## Assign sales tax codes to report lines

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  In the **Sales tax codes** form, on the **Report setup** FastTab, in the **Sales tax payable** field, select a reporting code for sales taxes that are due to the tax authorities. The reporting code corresponds to a box number on the sales tax form for your country or region.

3.  In the **Sales tax receivable** field, select a reporting code to use for sales tax refunds that offset sales taxes that are due.

## See also

[Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\))

  


