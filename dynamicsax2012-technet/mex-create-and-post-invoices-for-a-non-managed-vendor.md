---
title: (MEX) Create and post invoices for a non-managed vendor
TOCTitle: (MEX) Create and post invoices for a non-managed vendor
ms:assetid: bcff924c-9e6b-4553-9fe0-c3c765abe9a3
ms:mtpsurl: https://technet.microsoft.com/library/Hh242772(v=AX.60)
ms:contentKeyID: 36059145
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- invoice
- non-managed vendor
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create and post invoices for a non-managed vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Journal voucher** form to enter petty cash or minor expense transactions that are not posted directly to a vendor account, and then post an invoice for a non-managed vendor. To post invoice transactions for non-managed vendors, you must select the account type as **Ledger**, **Project**, or **Bank**. Petty cash or minor expense transactions that include Value Added Tax (VAT) should be declared in the purchase VAT book and in the Declaración Informativa de Operaciones con Terceros (DIOT) report. For more information, see [(MEX) Generate the DIOT declaration report (DIOTDeclaration\_MX)](mex-generate-the-diot-declaration-report-diotdeclaration-mx.md).

For DIOT declaration purposes, you must specify additional information, such as the Registro Federal del Contribuyentes (RFC) number, Clave Única de Registro de Población (CURP) number, vendor name, and the operation type for these vendor invoice transactions. Before you create and post an invoice, you must set up a sales tax code, sales tax group, and item sales tax group for purchase transactions with non-managed vendors. For more information, see [Setting up sales tax groups and item sales tax groups](setting-up-sales-tax-groups-and-item-sales-tax-groups.md).

Use the following procedures to create and post invoices for a non-managed vendor.

## Set up a sales tax code

Use the **Sales tax codes** form to specify additional vendor details for a non-managed vendor purchase transaction.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N to create a new sales tax code. For more information, see [Create various kinds of sales tax codes](create-various-kinds-of-sales-tax-codes.md).

3.  Click the **General** tab, and select the **Additional information** check box to indicate that purchases and journal transactions must include additional vendor tax details. You can use this information to generate a DIOT.

4.  Close the form to save your changes.

## Create and post a vendor invoice for a non-managed vendor

Use the **Journal voucher** form to create and post an invoice containing the tax registration IDs and other vendor details.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Press CTRL+N to create a new journal. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines** to open the **Journal voucher** form. For more information, see [Post invoices in an invoice journal](post-invoices-in-an-invoice-journal.md).

4.  On the **Overview** tab, in the **Account type** field, select the account type as **Ledger**, **Project**, or **Bank**.

5.  In the **Sales tax group** field, select the sales tax group.

6.  In the **Item sales tax group** field, select the item sales tax group.

7.  Click the **Additional information** tab, and in the **Type of operation** field, select the type of service provided by the non-managed vendor.
    

    > [!NOTE]
    > <P>The fields on the <STRONG>Additional information</STRONG> tab are available only if you select <STRONG>Account type</STRONG> as <STRONG>Ledger</STRONG>, <STRONG>Bank</STRONG>, or <STRONG>Project</STRONG> and specify the <STRONG>Sales tax group</STRONG> and <STRONG>Item sales tax group</STRONG>.</P>



8.  In the **Type of operation** field, select the operation type as **03: professional services**, **06: rent/lease**, or **85: Others**.

9.  In the **Type of vendor** field, select the vendor type as **04: domestic vendor** or **15: domestic/global vendor**.

10. In the **RFC number** field, enter the 12-character RFC number of the vendor.
    

    > [!NOTE]
    > <P>The first three characters represent the company name, the next six characters represent the date of company registration (YYMMDD), and the last three characters are assigned randomly by the government.</P>



11. In the **CURP number** field, enter the 18-character CURP number of the vendor.
    

    > [!NOTE]
    > <P>The first four characters represent the individual’s name, the next six characters represent the date of birth (YYMMDD), the next character represents the gender (M: Female or H: Male), the next two characters represent the state where the person resides, and the last five characters are assigned randomly by the tax authority.</P>



12. In the **Vendor name** field, enter the name of the vendor.

13. Click **Post** \> **Post** to post the vendor invoice for a non-managed vendor.

14. Close the forms to save your changes.

## See also

[Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\))

[Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\))

  


