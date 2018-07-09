---
title: (IND) Create a vendor invoice with VAT details
TOCTitle: (IND) Create a vendor invoice with VAT details
ms:assetid: b8590d24-961b-4549-b927-96b2b65fac17
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664810(v=AX.60)
ms:contentKeyID: 49386140
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create a vendor invoice with VAT details [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must record an invoice that you received from a vendor in the **Vendor invoice pool excluding posting details** form. (Click **Accounts payable** \> **Journals** \> **Invoices** \> **Vendor invoice pool excluding posting details**.)


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a new journal.

3.  Enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa557917(v=ax.60)">Journal header (form)</A> in the Applications and Business Processes Help.</P>



4.  Click **Lines** to open the **Journal voucher** form.

5.  Click **Functions** \> **Invoice pool excl. posting** to open the **Invoice pool excl. posting** form.

6.  Click the invoice line to select the invoice to transfer to the invoice journal.

7.  Click **Accept** to transfer the invoice to the invoice journal lines.
    

    > [!NOTE]
    > <P>The journal voucher contains the values of the invoice selected from the <STRONG>Invoice pool excl.</STRONG> posting form. You can modify the fields under the <STRONG>VAT</STRONG> field group before posting.</P>



8.  Click the **Tax information** tab and select the Tax Identification Number (TIN) in the **Tax Identification Number (TIN)** field.

9.  Select the VAT goods type for the transaction line in the **VAT goods type** field.

10. Enter the percentage of purchase amount that is not used to manufacture taxable goods in the **Non recoverable pct.** field.

11. Post the journal.
    
    The calculated VAT amount for the transaction is posted to the ledger accounts specified in the **Tax Identification Number (TIN)** field.

## See also

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/en-us/library/jj678053\(v=ax.60\))

[(IND) Define TINs for vendors](ind-define-tins-for-vendors.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

