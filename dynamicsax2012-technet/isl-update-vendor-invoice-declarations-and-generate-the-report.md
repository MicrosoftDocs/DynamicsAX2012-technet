---
title: (ISL) Update vendor invoice declarations and generate the report
TOCTitle: (ISL) Update vendor invoice declarations and generate the report
ms:assetid: cccf1d59-5017-4986-ba85-69acac56f94f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242905(v=AX.60)
ms:contentKeyID: 36059455
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- declaration
- Iceland
- vendor invoice
---

# (ISL) Update vendor invoice declarations and generate the report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can enter transactions for payments made to vendors and update a vendor's invoice declaration in various accounting forms. You can enter information about vendor invoices, create project expense transactions for payments made from the invoices, and post the invoices. Use the procedures to update invoice declaration. You can also generate an invoice declaration text file for a vendor or a subcontractor.

## Update the invoice declaration in the Purchase order form

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select an existing purchase order.
    
    –or–
    
    Click **Purchase order** to create a new purchase order. For more information, see [Create a purchase order](create-a-purchase-order.md). In the **Create purchase order** form, in the **Vendor account** field, select the vendor associated with the purchase order, and then click **OK** to return to the **Purchase order** form.

3.  Click the **Price and discount** FastTab, and in the **Currency** field, select the currency code.

4.  Click the **Setup** FastTab, and in the **Invoice declaration** field, modify the invoice declaration for the purchase order. The default value is updated from the **Vendors** form.

5.  Click **Purchase** \> **Confirm** to confirm the purchase order.

6.  Click **Receive** \> **Packing slip** to open the **Packing slip journal** form.

7.  In the **Product receipt** field, enter the packing slip number, and then click **OK**.

8.  Click **Invoice** \> **Invoice** to open the **Vendor invoice** form and post the invoice.

9.  In the **Number** field, enter the invoice number.

10. Click **Process** \> **Post** to post the vendor invoice.

11. Close the forms to save your changes.

## Update the invoice declaration in the Journal voucher – General journal form

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, enter the journal name.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Press CTRL+N to create a new record.

6.  In the **Account type** and **Account** fields, select **Vendor** and the vendor account number.

7.  In the **Offset account type** and **Offset account** fields, select the offset account type and offset account number. For more information, see [Post invoices in an invoice journal](post-invoices-in-an-invoice-journal.md) and [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

8.  Click the **Invoice** tab, in the **Invoice declaration** field, modify the invoice declaration for the vendor.

9.  Click **Validate** \> **Validate** to validate the invoice.

10. Click **Post** \> **Post** to post the invoice.

11. Close the forms to save your changes.

## Update the invoice declaration in the Journal voucher – Invoice register form

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, enter the journal name.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Press CTRL+N to create a new record. For more information, see [Enter and post invoices in the Invoice register form](enter-and-post-invoices-in-the-invoice-register-form.md).

6.  In the **Date** field, select the posting date. The voucher number is displayed in the **Voucher** field.

7.  In the **Account** field, select the account number for the current account type.

8.  In the **Invoice** field, enter the invoice number.

9.  In the **Debit** or **Credit** fields, enter the transaction amount.

10. In the **Approved by** field, select the employee that has to approve the journal.

11. Click the **General** tab, and in the **Invoice declaration** field, modify the invoice declaration for the vendor.

12. Click **Validate** \> **Validate** to validate the invoice.

13. Click **Post** \> **Post** to post the invoice.

14. Close the forms to save your changes.

## Update the invoice declaration in the Expense journal form

1.  Click **Project management and accounting** \> **Journals** \> **Expense**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, select the journal name.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Press CTRL+N to create a new record.

6.  In the **Project** and **Category** fields, select the project identification number and the category for the project..

7.  Click the **General** tab, and in the **Account** field, select the account number for the account type.

8.  In the **Offset account type** and **Offset account** fields, select **Vendor** and vendor account number.

9.  Click the **Invoice** tab, and in the **Invoice declaration** field, modify the invoice declaration ID for the vendor.
    

    > [!NOTE]
    > <P>The <STRONG>Invoice</STRONG> tab is available only if you select <STRONG>Vendor</STRONG> in the <STRONG>Offset account type</STRONG> field.</P>



10. Click **Validate** \> **Validate** to validate the invoice.

11. Click **Post** \> **Post** to post the invoice.

12. Close the forms to save your changes.

## Update the invoice declaration in the Invoice pool excl. posting form

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Vendor invoice pool excluding posting details**.

2.  Select an existing record, or press CTRL+N to create a new record.

3.  In the **Date** field, select the posting date.

4.  In the **Vendor account** field, select the vendor account number.

5.  In the **Currency** field, select the currency code. For more information, see [Enter vendor invoices in an invoice pool](enter-vendor-invoices-in-an-invoice-pool.md).

6.  Click the **Invoice** tab, and in the **Invoice declaration** field, modify the invoice declaration ID for the purchase transaction.

7.  Close the form to save your changes.

## Generating the vendor invoice declaration and text file

You can create an annual declaration that details the amounts paid to vendors and subcontractors, and then generate a text file of the report for upload to a government website. Click **Accounts payable** \> **Reports** \> **Statistics** \> **Vendor** \> **Vendor invoice declaration**.

In the **Vendor invoice declaration report** you can view the following information:

  - The amounts paid to vendors and subcontractors during the year. The report layout and .txt file can include negative amounts.

  - The currency type.

## See also

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Journal voucher - General journal (form)](https://technet.microsoft.com/en-us/library/aa591466\(v=ax.60\))

[Journal voucher - Invoice journal (form)](https://technet.microsoft.com/en-us/library/aa616218\(v=ax.60\))

[Journal voucher - Invoice register (form)](https://technet.microsoft.com/en-us/library/aa575517\(v=ax.60\))

[Expense journal (form)](https://technet.microsoft.com/en-us/library/aa600976\(v=ax.60\))

[Vendor invoice pool excluding posting details (form)](https://technet.microsoft.com/en-us/library/bb314782\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

