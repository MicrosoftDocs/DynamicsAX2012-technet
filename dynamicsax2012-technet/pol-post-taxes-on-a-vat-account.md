---
title: (POL) Post taxes on a VAT account
TOCTitle: (POL) Post taxes on a VAT account
ms:assetid: b02eb0c9-035b-45cb-9770-c46c0ccc23dc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711236(v=AX.60)
ms:contentKeyID: 49387054
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Post taxes on a VAT account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define the data for the VAT register that is used to post sales taxes to the VAT register in the NIP table. The NIP table code can be assigned to the general journal lines when the sales taxes are posted.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**. Click **Lines**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**. Click **Lines**.

2.  Press CTRL+N to create a new line.

3.  In the **Account type** field, select the type of account as **Ledger**.

4.  In the **Account** field, select the account number for the selected account type.

5.  In the **Debit** or **Credit** fields, enter the debit or credit amount.

6.  In the **Offset account type** field, select the account type for the offset account.

7.  In the **Offset account** field, select the offset account number.

8.  On the **General** tab, in the **Sales tax code** field, select the sales tax code. You can view the sales tax amount in the **Sales tax amount** field, for the selected sales tax code.

9.  In the **Sales tax group** and **Item sale tax group** fields, select the tax groups.

10. In the **Base amount for VAT** field, view or modify the base amount for VAT register.

11. On the **Invoice** tab, in the **Invoice** field, enter the invoice number.

12. In the **Document date** field, select the date of the document.

13. In the **Code** field, select the NIP code, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "General journal lines (form)" in the Applications and Business Processes Help.</P>



14. Click **Post** \> **Post** to post the journal.
    

    > [!NOTE]
    > <P>You can view the posted transactions in the <STRONG>VAT register</STRONG> report.</P>



## See also

[(POL) Create a NIP record to define VAT register data](pol-create-a-nip-record-to-define-vat-register-data.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

