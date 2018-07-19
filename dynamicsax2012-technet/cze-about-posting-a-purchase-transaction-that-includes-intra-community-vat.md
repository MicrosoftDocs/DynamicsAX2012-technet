---
title: (CZE) About posting a purchase transaction that includes intra-community VAT
TOCTitle: (CZE) About posting a purchase transaction that includes intra-community VAT
ms:assetid: 46845f03-1a5c-4211-899d-9f5e43edf46a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677515(v=AX.60)
ms:contentKeyID: 49384819
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) About posting a purchase transaction that includes intra-community VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you post a purchase transaction in the European Union (EU), and the transaction includes intra-community value-added tax (VAT), the following conditions are verified automatically:

  - The **Intra-community VAT** check box is selected for the negative sales tax code that is included in the sales tax group.

  - The sales tax direction is **Sales tax payable**.

  - The tax transaction is from a purchase.

  - The purchase is not a purchase credit note.

  - In the **Accounts payable parameters** form, the **Document date for intra-community VAT** check box is selected.

If the purchase transaction passes these verifications, two tax transactions are posted: one positive tax transaction and one negative tax transaction.

  - The positive sales tax transaction has a VAT register date that is set according to the VAT register date of the invoice posting. The sales tax direction is **Sales tax receivable**.

  - The negative sales tax transaction has a VAT register date that is set according to the document date. The sales tax direction is **Sales tax payable**.

## See also

[(CZE) About intra-community VAT](cze-about-intra-community-vat.md)

  


