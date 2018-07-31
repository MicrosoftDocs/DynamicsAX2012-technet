---
title: (IND) Split purchase documents
TOCTitle: (IND) Split purchase documents
ms:assetid: 87b4a04d-fdb4-402e-bf8a-c9fa2f11ef33
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678018(v=AX.60)
ms:contentKeyID: 49385979
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Split purchase documents 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can split an invoice based on delivery addresses, sites, and service codes. If the **Invoice** check box is cleared in the **Split based on delivery information** field group in the **Accounts payable parameters** form, an invoice is posted as a single invoice and is not split.

To post an invoice when the invoice lines have different delivery addresses and different tax account numbers (TANs), you must select the **Invoice** check box. To post an invoice when the invoice lines have different delivery addresses but the same TANs, clear the **Invoice** check box. In this case, the invoice is split based on the delivery addresses.

You can also select the **Product receipt** check box to split product receipts that have different delivery addresses and TANs.

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Updates**, and then select the **Product receipt** and **Invoice** check boxes. You can then post and split a product receipt or invoice that has different delivery addresses and TANs in the **Purchase order** form.

## See also

[(IND) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664793\(v=ax.60\))

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

[(IND) Split sales documents](ind-split-sales-documents.md)

  


