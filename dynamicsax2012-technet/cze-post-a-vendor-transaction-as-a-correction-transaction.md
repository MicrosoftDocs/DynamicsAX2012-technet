---
title: (CZE) Post a vendor transaction as a correction transaction
TOCTitle: (CZE) Post a vendor transaction as a correction transaction
ms:assetid: 4a993df8-b5b5-4496-a5dc-6db07c7e1612
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677520(v=AX.60)
ms:contentKeyID: 49384825
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Post a vendor transaction as a correction transaction [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create ledger transactions for a summary account and an arrival account if the account numbers, transaction date, voucher, document date, and amount in transaction currency are the same. Such transactions are posted as correction transactions in the general ledger.

1.  Click **Accounts payable** \> **Setup** \> **Vendor posting profiles**.

2.  Press CTRL+N to create a posting profile, or select an existing profile.

3.  Enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa551972(v=ax.60)">Vendor posting profiles (form)</A>.</P>



4.  On the **Setup** tab, in the **Account code** field, select an account code to specify whether the posting profile applies to a specific vendor, a group of vendors, or all vendors.

5.  In the **Account/Group number** field, select the account number of the vendor associated with the posting profile.

6.  In the **Summary account** field, select the ledger account for the vendor to which the posting profile is related.

7.  In the **Arrival** field, select the ledger account that the information about unapproved invoices is posted to. This information is entered in the invoice register.
    

    > [!NOTE]
    > <P>You must select the same ledger account in the <STRONG>Summary account</STRONG> and <STRONG>Arrival</STRONG> fields.</P>



8.  Press CTRL+S or close the form.

9.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

10. Press CTRL+N to create a new journal line or select an existing journal line. Enter the required details.

11. Click **Lines** to open the **Journal voucher** form.

12. In the **Account** field, select the vendor account.

13. In the **Invoice** field, enter the invoice number.

14. In the **Debit** or **Credit** fields, enter the debit or credit amount.

15. In the **Approved by** field, select the code of the employee who will approve the transaction.

16. Click **Post** to post the journal.

17. Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>For more information, see "Invoice register journal lines (form)" in the Applications and Business Processes Help.</P>



18. Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

19. Press CTRL+N to create a new journal line, and enter the required details.

20. Click **Lines** \> **Find vouchers** to open the **Find vouchers** form.

21. Click **Select** to select the vouchers, and click **OK**. New lines are displayed in the **Journal voucher** form.

22. Click **Post** to post the vendor transaction as a correction transaction.

23. Press CTRL+S or close the form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

