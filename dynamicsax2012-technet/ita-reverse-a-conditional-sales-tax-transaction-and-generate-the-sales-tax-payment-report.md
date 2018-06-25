---
title: (ITA) Reverse a conditional sales tax transaction and generate the sales tax payment report
TOCTitle: (ITA) Reverse a conditional sales tax transaction and generate the sales tax payment report
ms:assetid: 8a982476-3c0c-4a11-bc52-83c140459514
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209344(v=AX.60)
ms:contentKeyID: 36058467
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reverse
- Italy
- conditional sales tax
- sales tax payment report
---

# (ITA) Reverse a conditional sales tax transaction and generate the sales tax payment report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Conditional sales tax transactions are the sales tax transactions for which the sales tax is paid in proportion to the actual amount paid on the invoice. In accordance with the legislative requirement in Italy, you can reverse the conditional sales tax transactions for an open VAT period.

You can print the Sales tax payment report even if you have not posted invoices for the selected VAT period. The page numbers in the report are continuous even if there are no transactions for a period. The report includes blank pages for periods that have no transactions, and those pages are numbered. For example, if you generate a report for the period January 2011 to December 2011, and if you have no transactions for March, May, and November, the report will contain blank pages for those months.

However, you cannot post an invoice if the invoice posting date is earlier than the closing date shown in the **Close Italian sales tax book section** field in the **Italian sales tax book sections** form. The closing date is updated when the sales tax payment report is generated in the update mode. However, you can post or reverse an invoice if the VAT period is not closed.

To generate the sales tax payment report, you must complete the following tasks:

  - Set up a sales tax authority.

  - Set up the Italian sales tax book.

  - Set up the Italian sales tax regulations.

For more information, see [Set up conditional sales taxes](set-up-conditional-sales-taxes.md).

## Set up a sales tax authority

You must set up sales tax authorities with specific addresses, contact information, and report layouts.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**.

2.  Press CTRL+N to set up a new sales tax authority. For more information, see [Set up sales tax authorities](set-up-sales-tax-authorities.md).

3.  Click the **General** FastTab, and in the **Report layout** field, select **Italian report layout**.

4.  Select the **Print blank page with no transactions** check box to print a blank page in the sales tax payment report for periods that have no transactions.

5.  Select the **Separate summary register** check box to use a separate VAT book to number the summary sections.

6.  Close the form to save your changes.

## Set up the Italian sales tax book

Set up the Italian sales tax books to include the sales transactions in the sales tax report, and to print the VAT summary and the VAT payment in the report.


> [!NOTE]
> <P>Before you set up a sales tax book, you must set up a sales tax settlement period to close a sales tax book and include it in the final periodic sales tax report. For more information, see <A href="set-up-a-sales-tax-settlement-period.md">Set up a sales tax settlement period</A>.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Italian sales tax books**.

2.  Press CTRL+N to create a new Italian sales tax book.

3.  In the **Sales tax book** field, enter the sales tax book identification.

4.  In the **Sales tax book type** field, select **Sales** for the sales tax book type.

5.  In the **Settlement period** field, select a settlement period.

6.  In the **ATECOFIN Code** field, enter the tax code for reporting.

7.  Select the **Print summary and payment** check box to print the VAT summary and the VAT payment in the report.

8.  Close the form to save your changes.

## Set up the Italian sales tax regulations

You must set up specific number sequences for the sales tax books. After you assign the number sequence, the sales tax books remain linked to the sales tax purpose for which they are set up.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Italian sales tax book sections**.

2.  Press CTRL+N to create a new Italian sales tax book section.

3.  In the **Sales tax book** field, select a sales tax book.

4.  In the **Sales tax book section** field, select the sales tax book section that stores the transactions.

5.  In the **Number sequence code** field, select the number sequence code for the sales tax book reference.

6.  Close the form to save your changes.

## Generate the sales tax payment report

You can reverse a closed conditional sales tax transaction if the fiscal month is not closed. To reverse a transaction, you must post a free text invoice and settle the payment for the invoice. For more information, see [(ITA) Reverse a closed conditional sales tax transaction](ita-reverse-a-closed-conditional-sales-tax-transaction.md).

After you reverse the closed conditional sales tax transaction, you can generate and print an Italian sales tax payment report that contains all taxable transactions for a specific period.

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  In the **Settlement period** field, select a settlement period.

3.  In the **From date** and **Transaction date** fields, select the starting date and the ending date of the fiscal month.

4.  Select the **Update** check box to post the sales tax payment calculations for the settlement period.
    

    > [!NOTE]
    > <P>If you select this check box, the value in the <STRONG>Close Italian sales tax book section</STRONG> field of the <STRONG>Italian sales tax book sections</STRONG> form is updated with the closing date of the tax period.</P>



5.  Click **OK** to calculate the sales tax payment and to open the **Sales tax payment** form. The sales tax amounts are displayed in the amount fields, and can be modified. If you modify these amounts, the balance is updated in the **Sales tax balance** field.

6.  Click **OK** to generate and print the sales tax payments report.

## See also

[(ITA) Italian sales tax books (form)](https://technet.microsoft.com/en-us/library/aa620738\(v=ax.60\))

[Sales tax authorities (form)](https://technet.microsoft.com/en-us/library/aa552841\(v=ax.60\))

[(ITA) Italian sales tax book sections (form)](https://technet.microsoft.com/en-us/library/aa600627\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

