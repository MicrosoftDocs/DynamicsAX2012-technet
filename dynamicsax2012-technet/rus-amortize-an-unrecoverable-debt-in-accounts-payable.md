---
title: (RUS) Amortize an unrecoverable debt in Accounts payable
TOCTitle: (RUS) Amortize an unrecoverable debt in Accounts payable
ms:assetid: 1d9a14b9-bb9e-45e4-8073-3d09dbdcc498
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711453(v=AX.60)
ms:contentKeyID: 49387273
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Amortize an unrecoverable debt in Accounts payable 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can amortize unrecoverable debt, you must create the register journal for the period during which the amortization is run, and calculate and approve the **Accounts payable inventory act** register. The **Accounts payable movement** register need not be approved.

The transactions that are created are automatically settled with the unrecoverable invoices and any advance payments that have been received, and therefore, the unrecoverable debt is settled. After the update is performed, the amortized amount is displayed in the **Written off** field under the **Marked** field group.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Periodic** \> **Amortization** \> **Trade liabilities amortization**.

2.  In the **Calculation date** field, enter the transaction date. You can view the details of the debts with an expired claim date.

3.  Select the **Mark** check box to select the debts with an expired claim date that are to be amortized. You can view the total for the marked lines in the **Total** field under the **Marked** field group.
    

    > [!NOTE]
    > <P>Transactions are created in the ledger per vendor and numbered in accordance with the sequence that is designated for amortizing unrecoverable debt.</P>



4.  Click **Update** to update the total amount for the records selected for amortization.
    

    > [!NOTE]
    > <P>To view the original transactions, click <STRONG>Transaction</STRONG> under <STRONG>Vendors</STRONG> to open the <STRONG>Vendor transactions</STRONG> form.</P>



5.  Press CTRL+S or close the form.

## See also

[(RUS) Creditors debt cancellation (form)](https://technet.microsoft.com/en-us/library/jj711491\(v=ax.60\))

  


