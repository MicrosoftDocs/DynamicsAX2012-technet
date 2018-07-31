---
title: Restructure database schema for inherited tables
TOCTitle: Restructure database schema for inherited tables
ms:assetid: 9dc458c1-c403-4605-b9e9-9bb4666830c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ735270(v=AX.60)
ms:contentKeyID: 49693271
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Restructure database schema for inherited tables 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After Microsoft Dynamics AX 2012 R2 or R3 data upgrade has been completed, the **Restructure database schema for inherited tables** task flattens the database schema inherited from the source system. The resulting simplified table hierarchy is intended to improve performance by speeding data retrieval.

Perform the following steps to complete this task.

1.  In the **Data upgrade checklist** or the **Data upgrade checklist for in-place upgrade**, click the **Restructure database schema for inherited tables** task. The task generates a SQL query that is saved as \<drive\>:\\Users\\\<username\>\\AppData\\Local\\Temp\\1\\AX2012FlatteningDB.sql.

2.  Shut down the AOS.

3.  Open the file AX2012FlatteningDB.sql and copy its contents into a query window in SQL Server Management Studio.

4.  Run the query.

5.  Start the AOS.

6.  Synchronize the database.

7.  Mark the checklist task as complete.

  


