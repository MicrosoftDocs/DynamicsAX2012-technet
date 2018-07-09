---
title: (BRA) Cancel a transfer fiscal document
TOCTitle: (BRA) Cancel a transfer fiscal document
ms:assetid: bc7c72b3-0a14-44af-b2c5-7ff9d024b59a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933527(v=AX.60)
ms:contentKeyID: 50935140
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.InventTransferOrders
- BRA
- Brazil
- Forms.InventTransferFiscalDocCancel_BR
- Transfer fiscal documents
- Cancel transfer orders
- BR-00044
---

# (BRA) Cancel a transfer fiscal document [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to cancel a transfer fiscal document that is incorrect. When you cancel a transfer fiscal document, all of the ledger transactions and financial transactions are reversed.


> [!NOTE]
> <P>You cannot cancel a transfer fiscal document if the destination fiscal establishment has received the fiscal document.</P>



1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Select the transfer order to cancel. For more information, see [(BRA) Transfer orders (modified form)](https://technet.microsoft.com/en-us/library/jj910973\(v=ax.60\)).

3.  Click **Posting**, and then click **Cancel fiscal document** to open the **Cancel fiscal document** form.

4.  In the left pane, select the fiscal establishment to cancel the transfer fiscal document for.

5.  In the right pane, select the transfer fiscal document to cancel.

6.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Reason code** field, select the identification code of the reason to cancel the transfer fiscal document.

7.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Reason comment** field, enter or update the reason to cancel the transfer fiscal document.
    

    > [!NOTE]
    > <P>The reason for the cancellation must contain a minimum of 15 characters.</P>



8.  Click **OK** to cancel the transfer fiscal document.

## See also

[(BRA) About transfer orders](bra-about-transfer-orders.md)

[(BRA) Cancel transfer fiscal document (form)](https://technet.microsoft.com/en-us/library/jj911300\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

