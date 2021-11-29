---
title: Merge party IDs for vendor accounts across multiple legal entities
TOCTitle: Merge party IDs for vendor accounts across multiple legal entities
ms:assetid: cae044de-d4c4-4b36-aeb8-425a332585c5
ms:mtpsurl: https://technet.microsoft.com/library/Gg213660(v=AX.60)
ms:contentKeyID: 36059336
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Merge party IDs for vendor accounts across multiple legal entities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If multiple legal entities in your organization do business with the same vendor and each legal entity maintains a separate vendor account for that vendor, use this procedure to merge the party IDs for the vendor accounts across multiple legal entities. This enables you to make vendor payments for invoices in any of the legal entities that the vendor does business with.

1.  Click **Home** \> **Common** \> **Global address book**.

2.  Select the address book records that represent the vendor in each legal entity that you want to include in the mapping.

3.  On the **Action Pane**, click **Merge records**.

4.  Select the party ID to use for the merged address book record, and enter text that explains why you are merging the records.

5.  Click **Validate** to identify potential conflicts.

6.  Click **OK** to merge the records.

7.  Select the merged address book record that you selected the party ID for in step 4 and then expand the **Relationships** FactBox. The vendor account from each legal entity should be displayed.

## See also

[Party (form)](https://technet.microsoft.com/library/hh209008\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

[Merge global address book records](merge-global-address-book-records.md)

  


