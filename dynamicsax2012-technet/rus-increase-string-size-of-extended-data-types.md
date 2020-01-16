---
title: (RUS) Increase string size of extended data types
TOCTitle: (RUS) Increase string size of extended data types
ms:assetid: a2a257cb-1b2a-4891-87ed-f5fb5a839b16
ms:mtpsurl: https://technet.microsoft.com/library/JJ714196(v=AX.60)
ms:contentKeyID: 49651305
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Increase string size of extended data types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you upgrade from a Microsoft Dynamics AX 2009 system that has a GLS-EE/RU layer, the **Increase string size of extended data types** code upgrade task allows you to check your custom code for changes to the Name extended data type (EDT) and increase its maximum string length as needed. The task creates a development project in the Data Dictionary that includes the larger string size. This process helps you prevent mapping errors during data upgrade.


> [!NOTE]
> <P>Customization of the Name EDT for Russian and Eastern European localizations was provided as part of Microsoft Dynamics AX 2009 SP1. For more information about this service pack, see <A href="https://go.microsoft.com/fwlink/?linkid=257861">Service Pack 1 for Microsoft Dynamics AX 2009</A> on CustomerSource. Logon is required.</P>



## Upgrade scenarios

The following table lists possible upgrade scenarios and the action that the upgrade framework takes for each.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>Action</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SP1 was installed on the Microsoft Dynamics AX 2009 source system.</p></td>
<td><p>The user is prompted to allow the length property of the Name EDT to be modified automatically.</p></td>
</tr>
<tr class="even">
<td><p>SP1 was <em>not</em> installed on the Microsoft Dynamics AX 2009 source system.</p></td>
<td><p>A message informs the user that no action is being taken, because SP1 was not installed.</p></td>
</tr>
<tr class="odd">
<td><p>Customized code that changes the length property of the Name EDT was installed on the source system.</p></td>
<td><p>A message informs the user that no action is being taken, and that the Name EDT must be manually customized before upgrade.</p></td>
</tr>
</tbody>
</table>


## Analyze extended data types and apply changes

To detect the affected data types and to create a project to modify them, complete the following procedure.

1.  Open the **AOD code upgrade checklist** (**System administration** \> **Setup** \> **Checklists** \> **Code upgrade checklist** \> **AOD code upgrade checklist**).

2.  Ensure that all of the previous checklist items of the **AOD code upgrade checklist** have been marked as complete, then click **Increase string size of extended data types**.

3.  In the **Increase string size of extended data types** form, a line is displayed for each extended data type where the StringSize property in the baseline layer is greater than the StringSize property in the current Microsoft Dynamics AX 2012 R2 or R3 layer.

4.  For each extended data type that you wish to modify, mark the **Selected** field. The extended data type string length will be increased to the value specified in the **String size recommended** field.

5.  In the **String size recommended** field, you can manually set the maximum string size or accept the recommended value.

## See also

[(RUS) Increasing of the extended data types (form)](https://technet.microsoft.com/library/jj730941\(v=ax.60\))

  


