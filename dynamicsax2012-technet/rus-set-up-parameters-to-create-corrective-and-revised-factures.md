---
title: (RUS) Set up parameters to create corrective and revised factures
TOCTitle: (RUS) Set up parameters to create corrective and revised factures
ms:assetid: dda1a7d4-a86e-486e-b108-6ac33a588faa
ms:mtpsurl: https://technet.microsoft.com/library/JJ923599(v=AX.60)
ms:contentKeyID: 52075446
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Russia
- corrective
- revised facture
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters to create corrective and revised factures 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to set up parameters to create corrective and revised factures.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Set up accounts payable parameters for corrective factures

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Ledger and sales tax**.

3.  Select the **Control item dimension for correction lines** check box to control item dimensions for correction lines.

4.  Click **Number sequences**.

5.  In the **Number sequence code** field, select a number sequence code for the **Revising invoice internal number** reference.

## Set up accounts receivable parameters for corrective factures

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Ledger and sales tax**.

3.  Select the **Control item dimension for correction lines** check box to control item dimensions for correction lines.

4.  Click **Number sequences**.

5.  In the **Number sequence code** field, select a number sequence code for the **Revising sales invoice**, **Facture**, and **Corrective facture** references.

## Set up general ledger parameters for corrective factures

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Sales tax**.

3.  In the **Facture operation code delimiter** field, enter a symbol that is used as a delimiter for facture codes.

4.  In the **Sales/purchase book date and number delimiter** field, enter a symbol that is used as a delimiter for the facture date and number in the sales and purchase books.

5.  Click **Number sequences**.

6.  In the **Number sequence code** field, select a number sequence code for the **Facture** and **Prepayment facture** references.

## Set up a vendor account for invoicing

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select or create a vendor record, and then click **Edit**. For more information about how to create a vendor record, see [Create a vendor account](create-a-vendor-account.md).

3.  In the **Organization department** field, enter the organization department of the vendor.

4.  In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: On the **Miscellaneous details** FastTab, in the **Separate division code** field, select the identification code of the separate division that ships the items.

## Create facture operation codes

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Facture operation codes**.

2.  Create a new operation code. In the **Code** field, enter a facture operation code.

3.  In the **Name** field, enter the name of the facture operation.

4.  In the **Default operation type** field, select the default operation type.
    

    > [!NOTE]
    > <P>This field can be left empty.</P>



5.  Select the **Inherit** check box to indicate that the facture operation code can be inherited.

## See also

[(RUS) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj923609\(v=ax.60\))

[(RUS) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj733289\(v=ax.60\))

[(RUS) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj923603\(v=ax.60\))

[(RUS) Vendors (modified form)](https://technet.microsoft.com/library/dn126122\(v=ax.60\))

  


