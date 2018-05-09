---
title: TenderLineStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderLineStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinestatus(v=AX.60)
ms:contentKeyID: 62209668
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus.Historical
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus.Voided
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus.PendingCommit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus.NotProcessed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus.Committed
dev_langs:
- CSharp
- C++
- VB
---

# TenderLineStatus Enumeration

Represents the status of tender line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration TenderLineStatus
'Usage
Dim instance As TenderLineStatus
```

``` csharp
[DataContractAttribute]
public enum TenderLineStatus
```

``` c++
[DataContractAttribute]
public enum class TenderLineStatus
```

## Members

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>Default value, should not be used.</td>
</tr>
<tr class="even">
<td></td>
<td>NotProcessed</td>
<td>Tender line has not been processed yet.</td>
</tr>
<tr class="odd">
<td></td>
<td>PendingCommit</td>
<td>Tender line has been processed but not committed yet.
<p>For credit card equivalent is authorized.</p></td>
</tr>
<tr class="even">
<td></td>
<td>Voided</td>
<td>Tender line has been voided.</td>
</tr>
<tr class="odd">
<td></td>
<td>Committed</td>
<td>Tender line has been fully processed.
<p>For credit card equivalent is captured.</p></td>
</tr>
<tr class="even">
<td></td>
<td>Historical</td>
<td>Tender line is historical information.
<p>Tender line is just for displaying historical payments for a recalled order.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

