---
title: (BRA) Cancel a vendor NF-e
TOCTitle: (BRA) Cancel a vendor NF-e
ms:assetid: db8651ea-41d9-468b-bb2f-fee3b67dcf71
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933532(v=AX.60)
ms:contentKeyID: 50935146
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- cancel electronic fiscal document
- cancel NF-e
- vendor electronic fiscal document
- cancel vendor NF-e
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a vendor NF-e 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel a vendor nota fiscal eletrônica (NF-e) that is incorrect. You can cancel a vendor NF-e before you submit it to the Secretaria da Fazenda (SEFAZ). Alternatively, you can cancel the vendor NF-e after it is approved by SEFAZ.


> [!NOTE]
> <P>You can cancel a vendor NF-e that was processed or approved. However, you can cancel an approved NF-e only if SEFAZ approves the cancellation.</P>



When you cancel a vendor NF-e, the original NF-e is marked as canceled, and all the ledger transactions and financial transactions are reversed.

## Cancel a vendor NF-e that is generated from a purchase order

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order that is associated with the original NF-e.

3.  On the **Action Pane**, on the **Purchase** tab, click **Cancel fiscal document** to cancel the purchase order. For more information, see [(BRA) Cancel a vendor fiscal document](bra-cancel-a-vendor-fiscal-document.md).

## Cancel a vendor NF-e that is generated from a purchase complementary fiscal document

1.  Click **Accounts payable** \> **Common** \> **Fiscal documents** \> **All purchase complementary fiscal documents**.

2.  Select the purchase complementary fiscal document that is associated with the original NF-e.

3.  On the **Action Pane**, click **Cancel fiscal document** to cancel the purchase complementary fiscal document. For more information, see [(BRA) Cancel a purchase complementary fiscal document](bra-cancel-a-purchase-complementary-fiscal-document.md).

## See also

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj911277\(v=ax.60\))

[(BRA) Cancel vendor fiscal document (form)](https://technet.microsoft.com/en-us/library/jj923387\(v=ax.60\))

[(BRA) All purchase complementary fiscal documents (list page)](https://technet.microsoft.com/en-us/library/jj710524\(v=ax.60\))

[(BRA) Purchase complementary fiscal document (form)](https://technet.microsoft.com/en-us/library/jj710577\(v=ax.60\))

  


