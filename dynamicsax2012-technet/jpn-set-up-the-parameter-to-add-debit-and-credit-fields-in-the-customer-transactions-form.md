---
title: (JPN) Set up the parameter to add debit and credit fields in the Customer transactions form
TOCTitle: (JPN) Set up the parameter to add debit and credit fields in the Customer transactions form
ms:assetid: 95c330ab-ca49-4323-a15e-9dbfdb1b0a0f
ms:mtpsurl: https://technet.microsoft.com/library/Dn282398(v=AX.60)
ms:contentKeyID: 54906862
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustParameters
- MsDynAx060.Forms.CustParameters
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up the parameter to add debit and credit fields in the Customer transactions form 


_**Applies To:** Microsoft Dynamics AX 2012_

Use the **Accounts receivable parameters** form to set up the parameter to display the transaction currency amounts in separate debit and credit fields in the **Customer transactions** form.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  On the **General** FastTab, select the **Show amount in debit/credit columns** check box. The amount for each transaction is displayed in the **Amount currency debit** and the **Amount currency credit** fields in the **Customer transactions** form.

You can also use extended data types (EDTs) to create debit and credit columns in the ledger transaction forms in the **Accounts receivable** module. In the **AmountCurDebCred** extended data type **Properties** pane, specify the values in the following fields:

  - In the **Label** field, enter the combined modified label name for the debit and credit fields, separated by spaces. For example, you can change the label name to AmountCurrDr               AmountCurrCr.

  - In the **DisplaceNegative** field, enter a numeric value to increase the width of the field in the form. For example, enter 50.

For more information about how to use EDTs to create debit and credit columns, go to [Extended Data Types (EDTs)](https://technet.microsoft.com/library/ed713410-76c7-4b4e-9a27-a5ce9764743e.aspx), [Best Practices for Extended Data Types](https://technet.microsoft.com/library/34c58dad-942e-4c83-b374-4e0ec92d4ac2.aspx), and [Extended Data Type Properties](https://technet.microsoft.com/library/07eca44e-0ac8-4b08-906f-efaeabdf03fe.aspx).

## See also

[(JPN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj664964\(v=ax.60\))

[Customer transactions (form)](https://technet.microsoft.com/library/aa634902\(v=ax.60\))

[(JPN) Set up the parameter to add debit and credit fields in the Vendor transactions form](jpn-set-up-the-parameter-to-add-debit-and-credit-fields-in-the-vendor-transactions-form.md)

[How to: Create Tables](https://technet.microsoft.com/library/e83b5c11-f77b-4eb5-b57b-e73ad0fd4b3e.aspx)

[How to: Create an Extended Data Type](https://technet.microsoft.com/library/6292481f-1d73-46e9-8b46-18ab7de9a71d.aspx)

[Best Practices for Extended Data Type Properties](https://msdn.microsoft.com/library/aa621435\(v=ax.50\).aspx)

  


