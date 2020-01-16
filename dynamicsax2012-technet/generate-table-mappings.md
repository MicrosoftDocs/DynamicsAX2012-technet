---
title: Generate table mappings
TOCTitle: Generate table mappings
ms:assetid: 20967372-506e-4848-babf-fdc4f625c4f0
ms:mtpsurl: https://technet.microsoft.com/library/Gg751365(v=AX.60)
ms:contentKeyID: 35132573
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- tables
- fields
- upgrade
- columns
---

# Generate table mappings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Generate table mappings** task in the **Data upgrade checklist** creates the mapping between the tables and fields in the Microsoft Dynamics AX source database and the tables and fields that were created in the Microsoft Dynamics AX 2012 database during the **Create tables** step in the **Data upgrade checklist**.

Before you start the **Generate table mappings** task, you must complete the **Data upgrade checklist** steps **Connect to source database** and **Create tables**. If any errors were generated in the **Create tables** step, you must fix them before you proceed with mapping the tables and fields, otherwise the mapping will be incorrect.

## Generate table and field mappings

To generate mapping between tables and fields in the source and target databases, perform the following steps:

1.  In the **Data upgrade checklist**, click **Generate table mappings**.
    
    The upgrade framework begins the mapping process and, when mapping is complete, opens the **Table mapping between source and target systems** form. This form provides separate tabs where you can see all the tables and fields from the source database and how they are mapped to tables and fields in the target database. You can also view a list of the extended data types that are used in the source fields and have been brought into the target database.

2.  Review the mapping on the **Tables** and **Fields** tabs in the form and note any errors.

3.  Address mapping errors and rerun the **Generate table mappings** step.


> [!IMPORTANT]
> <UL>
> <LI>
> <P>If you encounter a mapping error, you may need to implement a presynchronization script that defines a mapping for the source table and field. For more information, see the white paper <A href="https://go.microsoft.com/fwlink/?linkid=196559%26clcid=0x409">How to write upgrade scripts in Microsoft Dynamics AX 2012</A>.</P>
> <LI>
> <P>Customized solutions will frequently cause table mapping errors. For example, the addition of a new extended data type will create an error for every table where it occurs. You will not be able to complete upgrade until you write and implement presynchronization scripts to address schema differences you have introduced.</P>
> <LI>
> <P>For testing purposes, it is possible to perform an upgrade on the non-customized portions of your installation and to ignore failed, customized tables using the <STRONG>Continue</STRONG> button on the <STRONG>Table mapping between source and target systems</STRONG> form. The affected tables will not be copied, but the rest of the upgrade can proceed.</P>
> <LI>
> <P>You cannot proceed to the next <STRONG>Data upgrade checklist</STRONG> step, <STRONG>Generate upgrade task prioritization</STRONG>, until you address any errors in table and field mapping. If you do, data upgrade on the target system will fail.</P></LI></UL>



## Mapping errors

You may encounter the following table-mapping errors for tables that are listed on the **Tables** tab in the **Table mapping between source and target systems** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Status</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>OK</strong></p></td>
<td><p>Mapping for the table is complete without error.</p></td>
</tr>
<tr class="even">
<td><p><strong>No mapping defined</strong></p></td>
<td><p>Mapping has not been created because no applicable metadata was found in the Microsoft Dynamics AX 2012 database.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Field error</strong></p></td>
<td><p>An error has occurred that resulted in a source field not being mapped to a target field. The error could be that there is an inconsistency in the field data type, no field to import, or a string-length difference in the field name.</p>
<p>You can see which fields have errors on the <strong>Fields</strong> tab.</p></td>
</tr>
<tr class="even">
<td><p><strong>Mapping conflict</strong></p></td>
<td><p>Two source-database tables are mapped to the same target table. You must resolve the conflict by renaming the table or assigning it a different ID.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Waiting on source</strong></p></td>
<td><p>A source table is still being used in preprocessing on the Microsoft Dynamics AX source system.</p></td>
</tr>
<tr class="even">
<td><p><strong>Target table not empty</strong></p></td>
<td><p>The table that was created in the Microsoft Dynamics AX 2012 target database has data in it. The source data cannot be copied into a table that already contains data. Clear all data from the target table.</p></td>
</tr>
</tbody>
</table>

  


