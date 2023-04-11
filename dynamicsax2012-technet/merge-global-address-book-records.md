---
title: Merge global address book records
TOCTitle: Merge global address book records
ms:assetid: c0ea8414-672d-4cf0-8700-3bb23b2f0293
ms:mtpsurl: https://technet.microsoft.com/library/Hh575243(v=AX.60)
ms:contentKeyID: 39555404
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Merge global address book records 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

At times, you might want to merge two or more party records into a single record. This can occur if you have created one or more duplicate party records, either on purpose or unintentionally.

When you merge party records, you select one record to keep. The information from the other records is merged into the first record. For example, you discover that information about Fabrikam is stored in three party records called A, B, and C. You decide to keep party record A. The information that is stored in party records B and C will be merged into party record A.

In some situations, party records cannot be merged.

  - You cannot merge party records that are associated with the same party role, such as a customer or vendor, in the same legal entity (LE). For example, party A is associated with a customer in LE 123, and party B is associated with a different customer in LE 123. These party records cannot be merged because the merged party record would be associated with multiple customers in the same LE, which is not allowed. However, the records can be merged if party B is associated with a vendor in LE 123, or with a customer in a different legal entity.

  - You cannot merge internal party organization records in the same legal entity, team, or operating unit.

## Merge party records

1.  Click **Home** \> **Common** \> **Global address book**.

2.  Select the records that you want to merge.

3.  On the **Action Pane**, on the **Global address book** tab, in the **Maintain** group, click **Merge records**.

4.  In the **Merge party records** form, in the **Select the party to retain** field, select the record that you want to keep. Information from the other selected records will be merged into this record.

5.  Select **Validate** to verify that the selected records can be merged.

6.  Click **OK**.

  


