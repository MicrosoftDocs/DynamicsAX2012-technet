---
title: 'Key tasks: Recurring free text invoices'
TOCTitle: 'Key tasks: Recurring free text invoices'
ms:assetid: e8bfcf86-86a2-48a3-b9f5-ee21d18c4248
ms:mtpsurl: https://technet.microsoft.com/library/Hh227473(v=AX.60)
ms:contentKeyID: 36059840
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- free text invoices
- free text invoice
- overview of recurring free text invoice
- free text recurrence
- invoice recurrence
audience: Application User
ms.search.region: Global
---

# Key tasks: Recurring free text invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Recurring invoices are used to invoice customers regularly for the same amount.

## What do you want to do?

Create a recurring free text invoice template

Assign a free text invoice template to a customer and enter recurrence details

Generate recurring invoices

Post recurring free text invoices

Print recurring free text invoices

Find form help

Find related tasks

## Create a recurring free text invoice template

Use this procedure to create a recurring free text invoice template.

1.  Click **Accounts receivable** \> **Setup** \> **Free text invoice templates**.

2.  Click **New**.

3.  Enter the template name and description.

4.  On the **Invoice lines** tab, assign an invoice line to the template, and then assign a main account to it and a unit count or amount.

5.  Optional: To distribute the line amount to multiple ledger accounts, click **Distribute amounts**. Enter the distribution information in the **Accounting distribution templates** form, and then close the form.

6.  Optional: Repeat steps 4 and 5 for additional invoice lines.

7.  Optional: To specify charges, such as freight and postage, click **Charges**.
    
    1.  Enter the charge information in the **Charges** form.
    
    2.  Optional: To distribute the charges line amount to multiple ledger accounts, click **Distribute amounts**. Enter the distribution information in the **Accounting distribution templates** form, and then close the form.
    
    3.  Close the **Charges** form.

8.  To save the changes, close the form.

Back to top

## Assign a free text invoice template to a customer and enter recurrence details

Use this procedure to assign a free text invoice template to a customer and specify when and how frequently the invoice will recur.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select the customer to assign the template to.

3.  On the **Invoice** tab, click **Recurring invoices** in the **Set up** group to open the **Recurring invoices** form.

4.  Click **New**.

5.  Select the template.

6.  Enter the recurrence start date, select the recurrence pattern, and specify any additional recurrence information.

7.  To save the changes, close the form.

Back to top

## Generate recurring invoices

Use this procedure to generate invoices that are due and that have free text invoice templates assigned to them.

1.  Click **Accounts receivable** \> **Periodic** \> **Recurring invoices** \> **Generate recurring invoices**.

2.  In the **Invoice date** field, enter the date to appear on the invoices.

3.  Select the template to generate invoices for.

4.  Click **OK**. A message will be displayed indicating that the invoice generation was successful.

Back to top

## Post recurring free text invoices

After recurring invoices have been generated, use this procedure to post the invoices.

1.  Click **Accounts receivable** \> **Periodic** \> **Recurring invoices** \> **Post recurring invoices**.

2.  On the **Action Pane**, click **Post**.
    

    > [!NOTE]
    > <P>If the <STRONG>Post</STRONG> button is not available and your organization requires a review process for free text invoices, the invoice might not have been submitted or approved. If you have not submitted the invoice for approval, click <STRONG>Submit</STRONG>. To view the status of a submitted invoice, click <STRONG>Actions</STRONG> &gt; <STRONG>View history</STRONG>.</P>



3.  Close the form.

Back to top

## Print recurring free text invoices

After recurring invoices have been posted, use this procedure to print the invoices.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, click **Print** \> **Range**.

3.  In the **Print customer invoice** form, select a range of customers, a range of dates, or both.

4.  Select the **Use print management destination** check box to print the invoice using the print settings that have been set up. To specify the printer destinations for the invoice, click **Printer setup**, and then click **OK** when you are finished.

5.  In the **Print customer invoice** form, click **OK**. The invoice is sent to the printer destination that is specified. The total of the amounts on the invoice lines and any charges are displayed on the invoice.

6.  Close the form.

Back to top

## Find form help

[Post recurring invoices (form)](https://technet.microsoft.com/library/hh242255\(v=ax.60\))

[Customer recurring invoice totals (form)](https://technet.microsoft.com/library/hh209605\(v=ax.60\))

[Generate recurring invoices (form)](https://technet.microsoft.com/library/hh227533\(v=ax.60\))

[Recurring invoice lines (form)](https://technet.microsoft.com/library/hh242234\(v=ax.60\))

[Accounting distribution templates (form)](https://technet.microsoft.com/library/hh209574\(v=ax.60\))

[Customer invoice recurrence history (form)](https://technet.microsoft.com/library/hh209441\(v=ax.60\))

[Customer recurring invoice (form)](https://technet.microsoft.com/library/hh209471\(v=ax.60\))

[Charges template (form)](https://technet.microsoft.com/library/hh208578\(v=ax.60\))

[Charges transactions (form)](https://technet.microsoft.com/library/aa633876\(v=ax.60\))

## Find related tasks

[Create charges codes](create-charges-codes.md)

  


