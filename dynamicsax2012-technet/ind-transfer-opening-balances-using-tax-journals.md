---
title: (IND) Transfer opening balances using tax journals
TOCTitle: (IND) Transfer opening balances using tax journals
ms:assetid: 358de990-df61-4348-a26d-770010148264
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664612(v=AX.60)
ms:contentKeyID: 49385689
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Transfer opening balances using tax journals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can use the **Tax journal** form to transfer opening balances from ledger accounts to the General journal or to post the adjustment entries when you select the ledger account of another tax component in an offset account.

It is not mandatory to create a tax journal for sales tax.


> [!NOTE]
> <P>To create a line for a tax journal, the <STRONG>Sales tax</STRONG> check box must be selected in the <STRONG>General parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**. Select or create a journal, and then click **Lines**. In the **Journal voucher** form, click **Functions** \> **Create tax journal**.

2.  Select the **India sales tax** in the **Tax type** field.
    

    > [!NOTE]
    > <P>The display of the sales tax registration number and the tax component is based on the type of tax selected in the <STRONG>Tax type</STRONG> field. If the type of tax in the <STRONG>Tax type</STRONG> field is changed to another tax type, the <STRONG>Tax ledger posting group</STRONG> field and the <STRONG>Tax registration number</STRONG> field will be cleared in the <STRONG>Tax journal</STRONG> form.</P>



3.  Select the tax ledger posting group for sales tax in the **Tax ledger posting group** field. View the tax registration number that is attached to the specified tax ledger posting group in the **Registration number** field.

4.  Select the date of posting for the selected tax type in the **To date** field.

5.  Press CTRL+N to create a new record for the tax journal.

6.  Select the tax component in the **Tax component** field.

7.  Select the ledger account that is defined for the tax ledger posting group, the sales tax registration number, and the tax component in the **Account** field.

8.  Enter the amount of the tax in the **Amount** field. You must enter a negative value for a credit value and a positive value for a debit value.

9.  Select the tax codes that the specified tax component is attached to in the **Tax code** field.

10. Click **Transfer** to transfer the information from the **Tax journal** form to the **Journal voucher** form.

11. Select the ledger account that the opening balance transaction is posted to in the **Offset account** field. If you have entered a negative amount in the **Amount** field in the **Tax journal** form, the tax amount is transferred to the ledger account that you specify in this field, and if you have entered a positive amount, the tax amount is subtracted from the ledger account.

12. Validate and post the journal. The excise record is updated with the journal details and the tax component amount.

## See also

[(IND) Tax journal ( form)](https://technet.microsoft.com/en-us/library/jj664732\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

