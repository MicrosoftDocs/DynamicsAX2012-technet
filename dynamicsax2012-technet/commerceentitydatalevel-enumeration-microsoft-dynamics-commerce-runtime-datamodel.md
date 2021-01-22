---
title: CommerceEntityDataLevel Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceEntityDataLevel Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitydatalevel(v=AX.60)
ms:contentKeyID: 62206694
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel.Identity
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel.Minimal
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel.Complete
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel.Extended
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel.Standard
dev_langs:
- CSharp
- C++
- VB
---

# CommerceEntityDataLevel Enumeration

Represents the various levels of data which an entity can contain.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CommerceEntityDataLevel
'Usage
Dim instance As CommerceEntityDataLevel
```

``` csharp
public enum CommerceEntityDataLevel
```

``` c++
public enum class CommerceEntityDataLevel
```

## Members

<table>
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
<td>Identity</td>
<td>The entity object contains identity-only information.</td>
</tr>
<tr class="even">
<td></td>
<td>Minimal</td>
<td>The entity object contains minimal information.</td>
</tr>
<tr class="odd">
<td></td>
<td>Standard</td>
<td>The entity object contains a level of data adequate for most situations.</td>
</tr>
<tr class="even">
<td></td>
<td>Extended</td>
<td>The entity object contains extended information.</td>
</tr>
<tr class="odd">
<td></td>
<td>Complete</td>
<td>The entity object contains all the information associated with it in the data store.</td>
</tr>
</tbody>
</table>


## Remarks

Observations: - Not all levels may apply to all entity types.

\- The exact information mapped to each level depends on the entity type.

\- The implicit data level also varies per entity type, and must be reviewed.

\- The implicit data level of the base class is Complete.

\- There isn't a 'None' data level, since every entity object instance must have an identity.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

