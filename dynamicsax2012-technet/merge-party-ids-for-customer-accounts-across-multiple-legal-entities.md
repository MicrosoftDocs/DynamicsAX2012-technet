---
title: Merge party IDs for customer accounts across multiple legal entities
TOCTitle: Merge party IDs for customer accounts across multiple legal entities
ms:assetid: e8b62f58-9306-40c0-b403-7e9b8cd43216
ms:mtpsurl: https://technet.microsoft.com/library/Gg243240(v=AX.60)
ms:contentKeyID: 36059838
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Merge party IDs for customer accounts across multiple legal entities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If multiple legal entities in your organization do business with the same customer and each legal entity maintains a separate customer account for that customer, use this procedure to merge the party IDs for the customer accounts across multiple legal entities. This enables you to print consolidated statements or receive customer payments for invoices in any of the legal entities that the customer does business with.

1.  Click **Home** \> **Common** \> **Global address book**.

2.  Select the address book records that represent the customer in each legal entity that you want to include in the mapping.

3.  On the **Action Pane**, click **Merge records**.

4.  Select the party ID to use for the merged address book record, and enter text that explains why you are merging the records.

5.  Click **Validate** to identify potential conflicts.

6.  Click **OK** to merge the records.

7.  Select the merged address book record that you selected the party ID for in step 4 and then expand the **Relationships** FactBox. The customer account from each legal entity should be displayed.

## See also

[Party (form)](https://technet.microsoft.com/library/hh209008\(v=ax.60\))

[Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\))

[Merge global address book records](merge-global-address-book-records.md)

  


