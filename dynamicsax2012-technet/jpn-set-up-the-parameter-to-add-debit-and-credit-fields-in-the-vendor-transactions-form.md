---
title: (JPN) Set up the parameter to add debit and credit fields in the Vendor transactions form
TOCTitle: (JPN) Set up the parameter to add debit and credit fields in the Vendor transactions form
ms:assetid: b521ce80-cfd9-4fd5-a2e5-655b34f78043
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn282399(v=AX.60)
ms:contentKeyID: 54906861
ms.date: 01/21/2017
mtps_version: v=AX.60
f1_keywords:
- Forms.VendParameters
- MsDynAx060.Forms.VendParameters
---

# (JPN) Set up the parameter to add debit and credit fields in the Vendor transactions form [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012_

Use the **Accounts payable parameters** form to set up the parameter to display the transaction currency amounts in separate debit and credit fields in the **Vendor transactions** form.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Select the **Show amount in debit/credit columns** check box. The amount for each transaction is displayed in the **Amount currency debit** and the **Amount currency credit** fields in the **Vendor transactions** form.

You can also use extended data types (EDTs) to create debit and credit columns in the ledger transaction forms in the **Accounts payable** module. In the **AmountCurDebCred** extended data type **Properties** pane, specify the values in the following fields:

  - In the **Label** field, enter the combined modified label name for the debit and credit fields, separated by spaces. For example, you can change the label name to AmountCurrDr               AmountCurrCr.

  - In the **DisplaceNegative** field, enter a numeric value to increase the width of the field in the form. For example, enter 50.

For more information about how to use EDTs to create debit and credit columns, go to [Extended Data Types (EDTs)](http://technet.microsoft.com/en-us/library/ed713410-76c7-4b4e-9a27-a5ce9764743e.aspx), [Best Practices for Extended Data Types](http://technet.microsoft.com/en-us/library/34c58dad-942e-4c83-b374-4e0ec92d4ac2.aspx), and [Extended Data Type Properties](http://technet.microsoft.com/en-us/library/07eca44e-0ac8-4b08-906f-efaeabdf03fe.aspx).

## See also

[(JPN) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710993\(v=ax.60\))

[(JPN) Vendor transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664966\(v=ax.60\))

[(JPN) Set up the parameter to add debit and credit fields in the Customer transactions form](jpn-set-up-the-parameter-to-add-debit-and-credit-fields-in-the-customer-transactions-form.md)

[How to: Create Tables](http://technet.microsoft.com/en-us/library/e83b5c11-f77b-4eb5-b57b-e73ad0fd4b3e.aspx)

[How to: Create an Extended Data Type](http://technet.microsoft.com/en-us/library/6292481f-1d73-46e9-8b46-18ab7de9a71d.aspx)

[Best Practices for Extended Data Type Properties](http://msdn.microsoft.com/en-us/library/aa621435\(v=ax.50\).aspx)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

