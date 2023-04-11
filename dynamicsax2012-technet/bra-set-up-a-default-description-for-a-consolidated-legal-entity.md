---
title: (BRA) Set up a default description for a consolidated legal entity
TOCTitle: (BRA) Set up a default description for a consolidated legal entity
ms:assetid: 1207e71e-5512-40c4-a205-dd402b11d59d
ms:mtpsurl: https://technet.microsoft.com/library/JJ710415(v=AX.60)
ms:contentKeyID: 49384307
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- company account
- BRA
- Brazil
- consolidated company account
- default description
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a default description for a consolidated legal entity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Default descriptions** form to set up transaction text for transactions. When you post a transaction, the transaction type is identified by using the default description and the transaction text that corresponds to the default description is posted to the ledger. The transaction text is printed on the day book and analytical ledger reports. You must use the %6 variable as part of the transaction text.

When you consolidate transactions and you have selected the **Transfer transactions only** check box in the **Consolidate** form, the transaction text for the consolidated legal entity is updated with the transaction text of the subsidiary legal entity. The %6 variable is replaced with the consolidated account number in the transaction text. For more information, see [(BRA) Transfer subsidiary legal entity transactions to a consolidated legal entity](bra-transfer-subsidiary-legal-entity-transactions-to-a-consolidated-legal-entity.md).

1.  Click **Organization administration** \> **Setup** \> **Default descriptions**.

2.  Create a default description.

3.  In the **Description** field, select **Ledger - consolidation**.

4.  In the **Language** field, select a language.

5.  In the **Text** field, enter the transaction text, including the %6 variable.

## See also

[(BRA) Setting up standard text in accounting transactions](bra-setting-up-standard-text-in-accounting-transactions.md)

  


