---
title: BOM Versions configuration key (BOMVersion)
TOCTitle: BOM Versions configuration key (BOMVersion)
ms:assetid: 6858a557-d8a3-477a-ad89-9bd8cbf7ec4d
ms:mtpsurl: https://technet.microsoft.com/library/Aa585534(v=AX.60)
ms:contentKeyID: 36997755
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Data_Dictionary.Configuration_Keys.BOMVersion
---

# BOM Versions configuration key (BOMVersion) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **BOM versions** configuration key controls access to bill of material (BOM) forms and functions when you work with BOM versions. BOM versions contain a list of items that make up an assembly, and are used in **Inventory management**.

If this key is enabled, you can do the following:

  - Use the same BOM for several item numbers

  - Attach more than one BOM to an item

  - Track changes in the BOM by creating new versions

  - Produce an item using a specific BOM

If this key is disabled, you cannot assign an item to a BOM

You can enable or disable this key in the **License configuration** form.

## Forms enabled by the configuration key

The following forms are available when the configuration key is enabled.

## Inventory management forms

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Bills of materials</strong></p></td>
<td><p><a href="https://technet.microsoft.com/library/aa587282(v=ax.60)">BOM (form)</a></p>
<p><a href="https://technet.microsoft.com/library/hh328668(v=ax.60)">Formula (form)</a></p></td>
</tr>
</tbody>
</table>


## Additional information about this configuration key

The following table provides information about how this configuration key relates to other configuration keys and license codes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>License code</p></td>
<td><p><strong>Trade and Logistics</strong></p></td>
</tr>
<tr class="even">
<td><p>Parent key</p></td>
<td><p><strong>Allow cost breakdown activation</strong></p></td>
</tr>
<tr class="odd">
<td><p>Child keys</p></td>
<td><p><a href="bom-approval-configuration-key-bomapprove.md">BOM approval configuration key (BOMApprove)</a></p>
<div class="alert">

> [!NOTE]
> <P>The configuration keys listed here may have additional child configuration keys. Click the link for more information about a configuration key.</P>


</div></td>
</tr>
</tbody>
</table>


For more information about how license codes and configuration keys work together, see [About license codes and configuration keys](https://technet.microsoft.com/library/aa548653\(v=ax.60\)).

  


