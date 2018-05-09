---
title: (RUS) Adjust counteragent transactions in accounts payable
TOCTitle: (RUS) Adjust counteragent transactions in accounts payable
ms:assetid: 9c91a0e5-7078-4c46-9e31-ac164eccbae7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678535(v=AX.60)
ms:contentKeyID: 49387763
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Adjust counteragent transactions in accounts payable 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An act of adjustment is a document used for financial analysis, and contains the following information:


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



  - Open total balance (balance of invoices/credit notes and balance of advances/returns) per counteragent (contract) at the start and end of the period.

  - Information about unpaid invoices from the previous period (credit/debit liabilities) and their payment and mutual reimbursement in the current period.

  - Information about received/shipped invoices or credit notes for the selected period, with information about payment and mutual reimbursement.

  - Information about advances/returns of cash (unsettled payments for the current period).

  - Information about advances/returns of cash (unsettled payments for the previous periods).

Use the **Act of adjustment (vendors)** form to generate the act of adjustment report.

1.  Click **Accounts payable** \> **Inquiries** \> **Act of adjustment**.

2.  In the **Vendor account** field, select the vendor account.

3.  Select the **Counteragent** check box to specify if the counteragent is both a vendor and customer. If so, you can select the customer account for the vendor in the **Vendors** form, in the **Customer account** field on the **General** tab.
    

    > [!NOTE]
    > <P>For more information, see "Vendors (form)" in the Applications and Business Processes Help.</P>



4.  In the **Date interval code** field, select the interval code for the report period.

5.  In the **From date** and **To date** fields, view or modify the starting and ending dates of the report period.
    

    > [!NOTE]
    > <P>You can view the dates specified in these fields based on the interval period code selected in the <STRONG>Date interval code</STRONG> field.</P>



6.  In the **Currency type** field, select the type of currency.

7.  In the **Currency** field, select the transaction currency.
    

    > [!NOTE]
    > <P>Select <STRONG>Indicated currency</STRONG> in the <STRONG>Currency type</STRONG> field to activate this field.</P>



8.  Select the **By data of counteragent** check box to automatically fill the sections of adjustment act which are to be completed by the counteragent.

9.  Select the **Delete zero balance** check box to prevent invoice lines with a zero balance or a balance that is equal to the amount of the invoice from inclusion in the report.

10. Select the **Contracts** check box to include contract information.

11. Select the **Documents** check box to include information about documents that create debts.

12. Click **OK** to open the **Act of adjustment** report for the selected vendor.

13. Double-click a line in the table to view the vendor transaction that created the selected line in the **Vendor transactions** form.

14. Press CTRL+S or close the form.

15. In the **Act of adjustment** report, click **Select** to modify the setup defined for the report in the **Act of adjustment (vendors)** form, and then click **OK**.

16. Click **Print** to print the report.

## See also

[(RUS) Act of adjustment (vendors) (form)](https://technet.microsoft.com/en-us/library/jj711488\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

