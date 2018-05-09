---
title: (RUS) Adjust counteragent transactions in accounts receivable
TOCTitle: (RUS) Adjust counteragent transactions in accounts receivable
ms:assetid: 4355c1a1-d8d2-4d60-8172-1ada2ba2c929
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665322(v=AX.60)
ms:contentKeyID: 49387411
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Adjust counteragent transactions in accounts receivable 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



An act of adjustment is a document used for financial analysis, and contains the following information:

  - Open total balance (balance of invoices/credit notes and balance of advances/returns) per counteragent (contract) at the start and end of the period.

  - Information about unpaid invoices from the previous period (credit/debit liabilities) and their payment and mutual reimbursement in the current period.

  - Information about received/shipped invoices or credit notes for the selected period, with information about payment and mutual reimbursement.

  - Information about advances/returns of cash (unsettled payments for the current period).

  - Information about advances/returns of cash (unsettled payments for the previous periods).

Click **Accounts receivable** \> **Inquiries** \> **Act of adjustment**. Use the **Act of adjustment (customers)** form to generate the act of adjustment report.

1.  Click **Accounts receivable** \> **Inquiries** \> **Act of adjustment**. to open the **Act of adjustment (customers)** form.

2.  In the **Customer account** field, select the customer account.

3.  Select the **Counteragent** check box to specify if the counteragent is both a customer and vendor. If so, you can select the vendor account for the customer in the **Customers** form, in the **Vendor account** field on the **General** tab.
    

    > [!NOTE]
    > <P>For more information, see "Customers (form)" in the Applications and Business Processes Help.</P>



4.  In the **Date interval code** field, select the interval code for the report period.

5.  In the **From date** and **To date** fields, view or modify the starting and ending dates of the report period.
    

    > [!NOTE]
    > <P>You can view the dates specified in these fields based on the interval period code selected in the <STRONG>Date interval code</STRONG> field.</P>



6.  In the **Currency type** field, select the type of currency.

7.  In the **Currency** field, select the transaction currency.
    

    > [!NOTE]
    > <P>Select <STRONG>Indicated currency</STRONG> in the <STRONG>Currency type</STRONG> field to activate this field.</P>



8.  Select the **By data of counteragent** check box to automatically fill the sections of the adjustment act that are to be completed by the counteragent.

9.  Select the **Delete zero balance** check box to prevent invoice balance lines with a zero balance or a balance that is equal to the amount of the invoice from inclusion in the report.

10. Select the **Contracts** check box to include contract information.

11. Select the **Documents** check box to include information about documents that create debts.

12. Click **OK** to open the **Act of adjustment** report for the selected customer.

13. Double-click a line in the table to view the customer transaction that created the selected line in the **Customer transactions** form.

14. Press CTRL+S or close the form.

15. In the **Act of adjustment** report, click **Select** to modify the setup defined for the report in the **Act of adjustment (customers)** form, and then click **OK**.

16. Click **Print** to print the report.

## See also

[(RUS) Settle a sales transaction manually](rus-settle-a-sales-transaction-manually.md)

[(RUS) Settle sales transactions periodically](rus-settle-sales-transactions-periodically.md)

[(RUS) Act of adjustment (customers) (form)](https://technet.microsoft.com/en-us/library/jj711728\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

