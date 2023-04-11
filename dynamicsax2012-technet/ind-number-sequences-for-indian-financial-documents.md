---
title: (IND) Number sequences for Indian financial documents
TOCTitle: (IND) Number sequences for Indian financial documents
ms:assetid: 134dd341-3bde-4ab1-b5a2-77a599ee7f26
ms:mtpsurl: https://technet.microsoft.com/library/JJ733169(v=AX.60)
ms:contentKeyID: 49685137
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- financial
- (IND)
- India
- Number sequences
- financial documents
audience: Application User
ms.search.region: India
---

# (IND) Number sequences for Indian financial documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Number sequences are used to generate required identifiers that are readable and unique for master data records and transaction records. A master data or transaction record that requires an identifier is referred to as a reference. Before you can create new records for a reference, you must set up a number sequence and then associate it with the reference. Number sequences generate various identifiers for transactions, documents, and master data. The enhanced number sequence framework enables you to configure the number sequences that are used throughout all of Microsoft Dynamics AX. The standard number sequence references, and also new number sequence references, are added specifically for Indian tax features. Indian number sequences have number sequence references specified for each Indian tax feature. By using the number sequence references, ledger vouchers are generated for the following:

  - EXIM incentive schemes

  - Withholding tax settlements

  - VAT deferments

  - Export shipping bills

  - TDS and TCS adjustments

  - TDS and TCD reversal vouchers

  - Tax set off vouchers

  - Charge as expense document vouchers

  - Legal documents and registers such as Goods receipt notes and Excise registers

To set up number sequences that are related to a particular module, you can use the **Parameters** form for the module.

To set up number sequences for incentive schemes, open the **General ledger parameters** form, and in the **Sales tax** area, click **Incentive schemes**.

## See also

[Number sequence overview](number-sequence-overview.md)

[Set up number sequences](set-up-number-sequences.md)

  


