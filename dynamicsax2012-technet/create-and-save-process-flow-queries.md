---
title: Create and save process flow queries
TOCTitle: Create and save process flow queries
ms:assetid: 2dcb7b6f-35a1-4ae2-af2a-38dd1b351493
ms:mtpsurl: https://technet.microsoft.com/library/Hh580598(v=AX.60)
ms:contentKeyID: 39519084
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and save process flow queries 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create queries that include selected processes, substances, and substance categories. These queries can be used to display a graphical representation of processes, substances, and substance categories in the **Process map** form. The queries that you create can contain one or more processes, substances, or substance categories. You can define the appropriate information for each query by specifying criteria such as the type of process or substance category.

You can create four types of process map:

  - **Model** – Display processes and their process references, but no flow data.

  - **Substance flow** – Display processes and the aggregate flows between them.

  - **Budget** – Display processes and the aggregate budget flows between them.

  - **Budget comparison** – Display processes and a comparison of the actual and budgeted flows between them.

For example, you want to create a model query that displays the usage of electricity and natural gas in all the Site 1 locations in the organization. Electricity and natural gas are indirect energies. In the query, you include the following elements for processes, substances, and substance categories.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Filter</p></th>
<th><p>Query elements</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Processes</strong></p></td>
<td><p>Site 1-Main warehouse</p>
<p>Site 1-Quaratine warehouse</p>
<p>Site 1-Transit warehouse</p>
<p>Site 1-Vendor warehouse</p></td>
</tr>
<tr class="even">
<td><p><strong>Substances</strong></p></td>
<td><p>Electricity</p>
<p>Natural gas</p></td>
</tr>
<tr class="odd">
<td><p><strong>Substance Categories</strong></p></td>
<td><p>Indirect energy</p></td>
</tr>
</tbody>
</table>


## Create a query

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Environmental processes** \> **Environmental process maps**.

2.  Click **New**. Enter a name for the query and a brief description of the information that is included in the query.

3.  Select the model type of the query, and then click **Query**.

4.  In the **Process map filter** form, enter the date range for the query, if a date range is appropriate.

5.  Select among the available processes, substances, and substance categories to create the query that is used to display information in a process map. Then click **Close**.

  


