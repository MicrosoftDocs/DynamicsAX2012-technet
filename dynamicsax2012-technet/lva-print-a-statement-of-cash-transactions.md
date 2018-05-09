---
title: (LVA) Print a statement of cash transactions
TOCTitle: (LVA) Print a statement of cash transactions
ms:assetid: 0f58bcbc-6c58-4e15-8115-f56f09871d05
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721447(v=AX.60)
ms:contentKeyID: 49730225
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LVA) Print a statement of cash transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



At the end of each month, all companies operating in Latvia are required to declare all cash transactions that exceed a stated regulatory limit. You can create a legally compliant report listing all account holders whose total incoming and outgoing cash payments exceeded a specified limit during the reporting period. Payment transactions are retrieved from the corresponding petty cash accounts and displayed in the **Cash transaction** **reporting** form. You specify a minimum limit and include additional filter criteria, such as the transaction date, currency type, and transaction amount, to select the relevant transactions. All payment transactions that exceed the specified limit and satisfy the filter criteria are marked for printing.

Incoming and outgoing payment transactions are categorized and displayed per payment transaction code in the report.

1.  Click **Cash and bank management** \> **Periodic** \> **Statement transactions**.
    

    > [!NOTE]
    > <P>Any transactions remaining for the prior reporting period are displayed by default.</P>



2.  Click **Transfer** to open the **Data transfer** form, and specify the date range for selecting payment transactions.

3.  Click **OK** to return to the **Cash transaction reporting** form.
    

    > [!NOTE]
    > <P>All transactions that were posted during the specified period are retrieved from the petty cash accounts and displayed in the form.</P>



4.  As necessary, update the following information for the selected transactions:
    
      - **Company registration number** − Enter the registration number of the company.
    
      - **Country/region** − Select the country or region that the payment was submitted to.
    
      - **Name** − Enter the name of the account holder.

5.  Click **Mark** to open the **Transactions marking** form.

6.  In the **Value limit** field, specify the minimum value of the transactions to be reported. All incoming or outgoing transactions that exceed the specified limit will be marked for printing.
    

    > [!NOTE]
    > <P>Click <STRONG>Select</STRONG> to include additional filter criteria, such as transaction date, currency type, and transaction amount.</P>



7.  Click **OK** to return to the **Cash transaction reporting** form.
    

    > [!NOTE]
    > <P>The <STRONG>Print</STRONG> check box is selected for all transactions that satisfy the selection criteria.</P>



8.  In the **Payment transaction code** field, select the default payment transaction code for the transactions marked for printing.

9.  Click **Print** to open the **Statement of transactions in cash** form.

10. In the **Responsible** field, select the employee who is responsible for generating and printing the statement.

11. In the **Tax authority** field, select the sales tax authority that the report will be submitted to.

12. Click **OK** to print the statement.

## See also

[(LVA) Set up payment transaction codes](lva-set-up-payment-transaction-codes.md)

[(LVA) Transaction code (form)](https://technet.microsoft.com/en-us/library/jj684600\(v=ax.60\))

[(LVA) Cash transaction reporting (form)](https://technet.microsoft.com/en-us/library/jj721453\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

