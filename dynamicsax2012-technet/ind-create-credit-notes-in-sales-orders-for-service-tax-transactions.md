---
title: (IND) Create credit notes in sales orders for service tax transactions
TOCTitle: (IND) Create credit notes in sales orders for service tax transactions
ms:assetid: 325f4b6b-4276-43d6-bb69-745816876cff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664596(v=AX.60)
ms:contentKeyID: 49385673
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create credit notes in sales orders for service tax transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When a customer returns sold goods using a credit note, the service tax amount that is calculated is reversed. When you post the sales credit note, the service tax amounts are debited to the interim service tax payable accounts.


> [!NOTE]
> <P>The procedure for invoicing a returned item for a service tax transaction is same as that of invoicing the credit note, except that you would select a returned item for the order type.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order and then on the **Action Pane**, on the **Sell** tab, in the **Create** group, click **Credit note** to create a credit note.

3.  Iin the **Create credit note** form, select the **Select all** check box to select all transactions for credit note creation.

4.  Select the **Tax as per original invoice** check box to apply the tax rate for service tax on the date when the original order was invoiced.

5.  Select the **Mark** check box to select individual transactions to include in the credit note.

6.  Post the credit note.

## See also

[(IND) Copy sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj664849\(v=ax.60\))

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

