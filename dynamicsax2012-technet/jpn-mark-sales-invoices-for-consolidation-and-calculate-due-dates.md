---
title: (JPN) Mark sales invoices for consolidation and calculate due dates
TOCTitle: (JPN) Mark sales invoices for consolidation and calculate due dates
ms:assetid: b7cf6ea2-e148-4ead-8bbd-7cc738341386
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664957(v=AX.60)
ms:contentKeyID: 49386541
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- JP - 00011
---

# (JPN) Mark sales invoices for consolidation and calculate due dates [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can consolidate several sales invoices each month. You must mark the sales invoices for consolidation, calculate due dates for payment, and post the consolidated invoice. The payment due date is based on the cutoff day that you specify, and on the holidays that you set up. If you specify the document date, which is the original transaction date, the due date is based on the document date instead of the invoice date.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line.

2.  In the **Sales order** form, click **Header view**, and then click **Edit** to modify the sales order.

3.  Select the **Target of consolidation** check box to indicate that the invoice for the sales order will be consolidated later.
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Consolidated invoice for customer</STRONG> check box in the <STRONG>Accounts receivable parameters</STRONG> form, and if the <STRONG>Consolidation day</STRONG> field in the <STRONG>Customers</STRONG> form is not set to zero.</P>



4.  Click the **Price and discount** FastTab.

5.  In the **Payment** field, select the terms of payment that have been marked for holiday due date control. For more information, see [(JPN) Set up the terms of payment and the cutoff day for a customer](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-customer.md).
    

    > [!NOTE]
    > <P>To view the most recently consolidated invoice identification number and the date of the sales order, click <STRONG>Postings</STRONG> on the <STRONG>General</STRONG> tab. The <STRONG>Consolidation ID</STRONG> and <STRONG>Date</STRONG> fields display the last consolidated invoice identification number, and the date.</P>



6.  On the **Invoice** tab, click **Invoice**.

7.  In the **Posting invoice** form, click **OK** to post the sales order.

8.  Close the forms.

9.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

10. Select the customer account for the posted sales invoice, and then click **Transactions**.

11. In the **Customer transactions** form, select the posted invoice, and then click the **Payment** tab. The due date for the selected invoice is displayed in the **Due date** field.

## See also

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\))

[(JPN) Terms of payment (modified form)](https://technet.microsoft.com/en-us/library/jj711223\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

