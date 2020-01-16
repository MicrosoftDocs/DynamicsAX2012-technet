---
title: Add additional tables to advanced queries
TOCTitle: Add additional tables to advanced queries
ms:assetid: e1c75504-c265-4eb9-837b-553bcb9d9eb6
ms:mtpsurl: https://technet.microsoft.com/library/Aa551356(v=AX.60)
ms:contentKeyID: 37822164
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add additional tables to advanced queries 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedure to include additional tables in the query.

1.  In the form where you want to apply an advanced filter, press CTRL+F3 to open the **Inquiry** dialog box.

2.  Right-click the table name in the **Structure** section.

3.  From the drop-down list, choose a table to include in the query.


> [!NOTE]
> <P>All tables in the drop-down list either have a one to many (<STRONG>1:n</STRONG>) or a many to one (<STRONG>n:1</STRONG>) relationship with the selected table.</P>
> <P>In a <STRONG>1:n</STRONG> relationship, each field in the selected table have one or more related records in the other table.</P>
> <P>In an <STRONG>n:1</STRONG> relationship, one or more fields in the selected table are related to the other table.</P>



## Example

You want to find a line in a Sales order that has an important note attached, but you have forgotten both the order number and customer name.

You decide to print the **Order lines** report, using advanced query options, but when you try to specify the query range, you realize that there is no field in the **Order lines** table related to document references. You must add an additional table to your query.

1.  In the **Structure** section, right-click the **Order lines** table, point to **1:n**, and then select the table **Document references**.

2.  Select the **Range** tab, select the **Document references** table, Select **Type** in the**Field** list, and then select **Note** in the **Criteria** list.

When you run the **Order lines** report, you only get the order lines with notes attached and can select the one you were looking for.

  


