---
title: (AUT) Create sales tax reporting codes
TOCTitle: (AUT) Create sales tax reporting codes
ms:assetid: 02885a0c-44e3-407f-99b7-2f4e861498e6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242102(v=AX.60)
ms:contentKeyID: 36055932
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create sales tax reporting codes
- sales tax reporting codes
audience: Application User
ms.search.region: Austria
---

# (AUT) Create sales tax reporting codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the sales tax reporting codes to generate a yearly or monthly Austrian VAT statement. The four-digit sales tax reporting code syntax is based on the structure of the VAT statement. In the VAT statement, amounts are displayed in the **Tax base amounts** and **Tax amounts** columns. Sales tax reporting codes that begin with 10 are included in the tax boxes in the **Tax base amounts** column. Codes that begin with 11 are contained in the tax boxes in the **Tax amounts** column. The last two digits of the sales tax reporting codes refer to the tax box number.

Example: The tax base amount corresponding to sales tax reporting code 1022 and the tax corresponding to the sales tax reporting code 1122 are reported in tax box 022.For each tax box in the VAT statement, you can create a sales tax reporting code and assign it to a sales tax code. These sales tax reporting codes are entered in the **Taxable sales** and **Sales tax payable** fields on the **Report setup** tab of the **Sales tax codes** form. For more information, see [Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Sales tax reporting codes**.

2.  Press CTRL+N to create a new sales tax reporting code. For more information, see [Sales tax reporting codes (form)](https://technet.microsoft.com/en-us/library/aa588316\(v=ax.60\)).

3.  In the **Report layout** field, select **Austrian report layout**.

4.  In the **Reporting code** field, enter the sales tax reporting code. This reporting code is printed in the PDF tax box and exported with the appropriate tags in an .xml file.

5.  In the **Report text** field, enter the text to print on the report for the selected sales tax reporting code.

6.  In the **Brief description** field, enter a brief description for the sales tax reporting code.

7.  Close the form to save your changes.

## See also

[(AUT) Generate an Austrian sales tax report](aut-generate-an-austrian-sales-tax-report.md)

[Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md)

  


