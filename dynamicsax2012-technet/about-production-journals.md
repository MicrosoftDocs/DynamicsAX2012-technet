---
title: About production journals
TOCTitle: About production journals
ms:assetid: 44ce0cb7-7406-4f09-ab39-07c625a61a59
ms:mtpsurl: https://technet.microsoft.com/library/Aa496978(v=AX.60)
ms:contentKeyID: 36056888
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About production journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Production order journals record the different item transactions that occur when you work with production orders. These item transactions have a direct effect on the company's financial records.

When you post a production journal, all item transactions are automatically transferred to the **General ledger**. The **General ledger** is the centralized location for financial data and information in Microsoft Dynamics AX 4.0. The information that is posted from various journals in the system is used in the **General ledger** when companywide financial transactions are calculated.  

## Production journal types

The journal types that are used in production are as follows:  

  - **Picking list** - This journal is a record of the raw materials that are drawn out of inventory.

  - **Route card** - This journal is a record of the route consumption.

  - **Job card** - This journal is a record of the operations resource consumption using feedback job cards.

  - **Reported as finished** - This journal is a record of all items that are finished.  

## Production journals and lines

Production journals are divided into two components: the journal itself and the journal lines or actual journal records.  

  - **Journals** - The production journal contains information that pertains to all entries. This information includes the journal type, name, and number; and, it collectively identifies which journal you are working with.  
       
    A production journal can also contain information such as status, the method that was used to post information, whether negative deduction is permitted, and whether certain kinds of errors are accepted.  

  - **Lines** - Journal lines reflect the actual records or entries present in the journal itself. These records can include a list of production materials ready for release, the amount of time consumed, the number of good and defective items, and so on. Because journal records contain item transactions that create financial transactions, the information in the records is also in the ledger.  

## See also

[About production posting](about-production-posting.md)

  


