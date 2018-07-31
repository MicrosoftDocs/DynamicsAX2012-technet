---
title: (POL) Reverse a vendor transaction
TOCTitle: (POL) Reverse a vendor transaction
ms:assetid: 3d85eed6-d109-44cd-a675-ca296e021e4a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678179(v=AX.60)
ms:contentKeyID: 49386901
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Reverse a vendor transaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can reverse a vendor transaction as correction to a vendor invoice or other vendor transaction. Before you post a reversal of a vendor transaction, set up parameters that define how the reversal is posted to the General ledger.


> [!NOTE]
> <P>You cannot reverse transactions that are posted in a closed fiscal year.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set parameters for corrections

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  In the **Accounts receivable parameters** form, click the **Invoice** link.

3.  To enable credit notes as corrections to vendor invoices, select the **Credit note as correction** check box.

4.  Click the **Number sequences** link. In the **Reference** field, locate the **Correction note** row, and then in the **Number sequence code** field, select the number sequence to use for vendor corrections.

5.  Press CTRL+S or close the form.

## Enter a correction

Use this procedure to reverse a vendor transaction.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **All vendors** list page, on the **Action Pane**, click **New** to create a vendor account, or open an existing vendor record.

2.  Click **Transactions** to open the **Vendor transactions** form.

3.  In the **Vendors** form, on the **Action Pane**, on the **Vendor** tab, click **Transactions**.

4.  In the **Vendor transactions** form, on the **Overview** tab, select the transaction to reverse.

5.  On the top menu, click **Reverse transaction**.

6.  In the **Transaction reversal** form, in the **Reversal posting date** field, select the date on which to post the transaction reversal.

7.  Enter a reason code and an optional reason comment for the reversal.
    

    > [!NOTE]
    > <P>Your organization might require a reason code for a transaction reversal.</P>



8.  Click **OK** to complete the transaction.

## See also

[(POL) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj678134\(v=ax.60\))

  


