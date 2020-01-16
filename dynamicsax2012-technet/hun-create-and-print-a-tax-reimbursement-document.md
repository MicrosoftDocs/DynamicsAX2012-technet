---
title: (HUN) Create and print a tax reimbursement document
TOCTitle: (HUN) Create and print a tax reimbursement document
ms:assetid: 95573223-4fbe-4ee2-ba23-0a287510d3a5
ms:mtpsurl: https://technet.microsoft.com/library/JJ664334(v=AX.60)
ms:contentKeyID: 49385422
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create and print a tax reimbursement document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can provide a tax reimbursement document to a customer who has paid value-added tax (VAT) to you. Customers can use the tax reimbursement document to claim a VAT reimbursement from authorities.

Before you can create a tax reimbursement document, you must set up the parameters for the document. For more information, see [(HUN) Set up parameters for tax reimbursement documents](hun-set-up-parameters-for-tax-reimbursement-documents.md).

The tax reimbursement document is available only if the customer is set up as a person in the **Customers** form. Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. In the **Customers** form, on the **General** FastTab, confirm that the **Record type** field is set to **Person**.

## Set up print management for a tax reimbursement document

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**.

2.  In the **Form setup** form, in the **General** area, click **Print management**.

3.  In the **Print management setup** form, in the **Module - accounts receivable** section, click **Tax reimbursement slip**.

4.  In the **Module - inventory management** section, in the **Picking list** group, select either **Original** or **Copy**.

5.  In the right pane, enter information about what to print.

6.  Optional: In the **Footer text** field, enter text to print at the bottom of the tax reimbursement document.

## Select invoice lines for a tax reimbursement document

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  In the **Invoice journal** form, on the **Overview** tab, select the customer invoice for which the customer is requesting tax reimbursement.

3.  Select the **Tax reimbursement** check box for the selected invoice.

4.  By default, on the **Lines** tab, in the **Tax reimbursement lines** field, all invoice lines are selected. Clear the check boxes for the invoice lines to exclude from the tax reimbursement document.

5.  On the **Overview** tab, on the menu bar, click **Tax reimbursement** \> **Original preview** to view the document before you print it.

6.  Optional: Click **Tax reimbursement** \> **Use print management** to modify the print settings, such as the number of copies to print.

7.  In the **View original** form, review the information, and then click **File** \> **Print** to print the tax reimbursement document.

When you print a tax reimbursement document, the document number that is assigned to the document is displayed in the **Invoice journal** form, in the **Tax reimbursement document** field. The **Tax reimbursement** check box is unavailable for the lines that you included in the tax reimbursement document.

## Settle a tax reimbursement

When your organization reimburses a customer for VAT, you must indicate the reimbursement in the invoice journal to prevent a duplicate reimbursement. Use the following procedure to settle invoice lines for which a customer received a VAT reimbursement.

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  In the **Invoice journal** form, on the **Overview** tab, select the customer invoice for which the customer received a VAT reimbursement.

3.  On the **Overview** tab, on the menu bar, click **Tax reimbursement** \> **Vat settled**.

The **Vat settled** check box is selected for the invoice and the invoice lines.

## See also

[(HUN) Set up a customer passport number](hun-set-up-a-customer-passport-number.md)

[(HUN) Customer invoice journal (modified form)](https://technet.microsoft.com/library/jj733167\(v=ax.60\))

  


