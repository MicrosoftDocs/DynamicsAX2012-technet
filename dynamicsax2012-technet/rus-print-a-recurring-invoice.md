---
title: (RUS) Print a recurring invoice
TOCTitle: (RUS) Print a recurring invoice
ms:assetid: 260017fe-14f1-4df0-b51b-7294ca0ee634
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733190(v=AX.60)
ms:contentKeyID: 49685158
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Print
- invoice
- recurring
- (RUS)
- Russia
audience: Application User
ms.search.region: Russia
---

# (RUS) Print a recurring invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Recurring invoices are invoices that are issued at regular intervals for the same amount. Some examples of recurring invoices are monthly rental fees, annual membership fees, and monthly retainers.

Complete the following procedures to print a recurring invoice:

1.  Create a recurring free text invoice template.

2.  Assign a free text invoice template to a customer, and enter recurrence details.

3.  Generate and post recurring free text invoices.

4.  Print recurring free text invoices.

## Create a recurring free text invoice template

Use this procedure to create a recurring free text invoice template.

1.  Click **Accounts receivable** \> **Setup** \> **Free text invoice templates**.

2.  Create a new free text invoice template.

3.  Enter the template name and description.

4.  Select the **VAT on payment** check box to indicate that value-added tax (VAT) is accrued, so that it can be paid to the tax authority after the invoice payment, and to process the VAT on payment principle.

5.  Select the **Prices include sales tax** check box to indicate that the invoice amount includes sales tax.

6.  On the **Invoice lines** FastTab, assign an invoice line to the template, and then assign a main account and a unit count or amount to it.

7.  In the **Measurement unit** field, enter the unit of measure for the invoice line.

## Assign a free text invoice template to a customer and enter recurrence details

Use this procedure to assign a free text invoice template to a customer, and to specify when and how frequently the invoice recurs.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select the customer to assign the template to.

3.  On the **Invoice** tab, in the **Set up** group, click **Recurring invoices** to open the **Recurring invoices** form.

4.  Click **New**.

5.  Select the template. Enter the recurrence start date, select the recurrence pattern, and specify any additional recurrence information.

6.  In the **Agreement ID** field, select the agreement registration number.

## Generate and post recurring free text invoices

Use this procedure to generate invoices that are due, and that have free text invoice templates assigned to them. After the invoices are generated, you can use the **Post recurring invoices** form to post them.

1.  Click **Accounts receivable** \> **Periodic** \> **Recurring invoices** \> **Generate recurring invoices**.

2.  In the **Invoice date** field, enter the date that appears on the invoices.

3.  Select the template to generate invoices for.

4.  Click **OK** to generate the invoice.

5.  Click **Accounts receivable** \> **Periodic** \> **Recurring invoices** \> **Post recurring invoices**.

6.  On the **Action Pane**, click **Post**.

## Print recurring free text invoices

After recurring invoices have been posted, use the **Print customer invoice** form to print recurring free text invoices.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, click **Print** \> **Range**.

3.  In the **Print customer invoice** form, select a range of customers, a range of dates, or both.

4.  Enter the account type, the from and to accounts, the type of date that is used, and the from and to date details.

5.  Select the **Use print management destination** check box to print the invoice by using the print settings that have been set up. To specify the printer destinations for the invoice, click **Printer setup**, and then click **OK**.

6.  In the **Print customer invoice** form, click **OK**. The invoice is sent to the printer destination that is specified. The total of the amounts on the invoice lines and the charges are displayed on the invoice.

## See also

[Post recurring invoices (form)](https://technet.microsoft.com/en-us/library/hh242255\(v=ax.60\))

[Customer recurring invoice totals (form)](https://technet.microsoft.com/en-us/library/hh209605\(v=ax.60\))

[Generate recurring invoices (form)](https://technet.microsoft.com/en-us/library/hh227533\(v=ax.60\))

[Recurring invoice lines (form)](https://technet.microsoft.com/en-us/library/hh242234\(v=ax.60\))

[Accounting distribution templates (form)](https://technet.microsoft.com/en-us/library/hh209574\(v=ax.60\))

[Customer invoice recurrence history (form)](https://technet.microsoft.com/en-us/library/hh209441\(v=ax.60\))

[Customer recurring invoice (form)](https://technet.microsoft.com/en-us/library/hh209471\(v=ax.60\))

  


