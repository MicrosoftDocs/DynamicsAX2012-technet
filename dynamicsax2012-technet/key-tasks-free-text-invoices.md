---
title: 'Key tasks: Free text invoices'
TOCTitle: 'Key tasks: Free text invoices'
ms:assetid: 1a677114-5983-4d48-8d00-4ab9ae531cd1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208454(v=AX.60)
ms:contentKeyID: 36056120
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- invoices
- free text
- invoice
- customer invoice
- customer invoices
- free text invoices
- free text invoice
---

# Key tasks: Free text invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A free text invoice is an invoice that is not attached to a sales order. A free text invoice contains a header and one or more lines for items or services that are not tracked in inventory. Use a free text invoice for sales that do not require a sales order, packing slip, and customer invoice. For example, you can use a free text invoice for a consulting fee or services fee, or for a miscellaneous fee for an event reimbursement.


> [!NOTE]
> <P>To create or review titres and bordereaux de titres related to a free text invoice, see <A href="fra-key-tasks-titres-de-recette-and-bordereaux-de-titre-public-sector.md">(FRA) Key tasks: Titres de recette and bordereaux de titre (Public sector)</A>. Titres and bordereaux de titre are available only if the following conditions are met:</P>
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



## What do you want to do?

Create a simple free text invoice

Create a complex free text invoice

Post and print a free text invoice

Print a pro forma invoice

Find form help

Find related tasks

## Create a simple free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, click **Free text invoice** to open the **Free text invoice** form.

3.  On the **Free text invoice header** FastTab, select the customer account. The default information for the customer account is displayed.

4.  Select a billing classification.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



5.  In the **Invoice lines** grid, enter a description, select the main account, and enter the quantity and unit price for the invoice line.

6.  On the **Line details** FastTab, enter any additional information.

7.  To save your changes without posting the invoice, click **Close**.

Back to top

## Create a complex free text invoice

Use this procedure to create a free text invoice that has multiple lines, distributions, and charges.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, click **Free text invoice** to open the **Free text invoice** form.

3.  On the **Free text invoice header** FastTab, select the customer account. The default information for the customer account is displayed.

4.  Select a billing classification.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



5.  In the **Invoice lines** grid, enter a description, select the main account, and enter the quantity and unit price for the invoice line.
    

    > [!NOTE]
    > <P>If the <STRONG>Public sector</STRONG> configuration key is selected, you can select a value in the <STRONG>Billing code</STRONG> field for any free text invoice line. Default information for the billing code is entered on the line. This default values are defined in the <STRONG>Billing codes</STRONG> form for the selected billing code.</P>



6.  Optional: To distribute the line amount to multiple ledger accounts, click **Distribute amounts** on the **Action Pane**. Enter the distribution information in the **Accounting distributions** form, and then close the form. For more information, see [Create accounting distributions for free text invoices](create-accounting-distributions-for-free-text-invoices.md).

7.  Optional: Repeat steps 3 through 6 for each additional invoice line.

8.  Optional: To specify charges, such as freight and postage, click **Charges** on the **Action Pane**.
    
    1.  In the **Charges transactions** form, enter the charge information.
    
    2.  Optional: To distribute the line amount for the charges to multiple ledger accounts, click **Distribute amounts**. Enter the distribution information in the **Accounting distributions** form, and then close the form.
    
    3.  Close the **Charges transactions** form.

9.  Optional: To verify the customer's credit limit, click **Totals** on the **Action Pane**. Click **Close**.

10. To save your changes without posting the invoice, click **Close**.

Back to top

## Post and print a free text invoice

Use this procedure when you are ready to send an invoice to a customer. To generate electronic invoices, you can print to the screen, to a file, or to an email message.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the invoice that you want to post. On the **Action Pane**, click **Post**.
    

    > [!NOTE]
    > <P>Your organization might require a review process for free text invoices. Therefore, if the <STRONG>Post</STRONG> button is not available, the invoice might not have been submitted or approved. If you did not submit the invoice for approval, click <STRONG>Submit</STRONG>. To view the status of a submitted invoice, click <STRONG>Actions</STRONG> &gt; <STRONG>View history</STRONG>. The <STRONG>Actions</STRONG> menu is available only if a workflow is activated.</P>



3.  In the **Post free text invoice** form, select the **Posting** check box and the **Print invoice** check box.

4.  To print the invoice by using the printing settings that have been set up, select the **Use print management destination** check box. Alternatively, to specify the printer destinations for the invoice, click **Printer setup**. Click **OK**.

5.  In the **Post free text invoice** form, click **OK**.
    
    The invoice is posted to the general ledger and sent to the printer destination that is specified. The invoice displays the total of the amounts on the invoice lines and any charges.

Back to top

## Print a pro forma invoice

You can prepare a pro forma invoice that you can send to a customer before the sale.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the invoice that you want to print. On the **Action Pane**, click **Post**.

3.  In the **Post free text invoice** form, clear the **Posting** check box, and select the **Print invoice** check box.

4.  To print the invoice by using the printing settings that have been set up, select the **Use print management destination** check box. Alternatively, to specify the printer destinations for the invoice, click **Printer setup**. Click **OK**.

5.  In the **Post free text invoice** form, click **OK**.
    
    The pro forma invoice is sent to the printer destination that is specified. The invoice displays the total of the amounts on the invoice lines and any charges.

Back to top

## Find form help

[Free text invoice (form)](https://technet.microsoft.com/en-us/library/aa556897\(v=ax.60\))

[Charges transactions (form)](https://technet.microsoft.com/en-us/library/aa633876\(v=ax.60\))

[Free text invoice totals (form)](https://technet.microsoft.com/en-us/library/aa597310\(v=ax.60\))

## Find related tasks

[Key tasks: Customer invoices](key-tasks-customer-invoices.md)

[Reprint a free text invoice](reprint-a-free-text-invoice.md)

[Set up Intrastat from a free text invoice](set-up-intrastat-from-a-free-text-invoice.md)

[Create charges codes](create-charges-codes.md)

[Place an Accounts receivable transaction on hold](place-an-accounts-receivable-transaction-on-hold.md)

[Correct a posted free text invoice](correct-a-posted-free-text-invoice.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

