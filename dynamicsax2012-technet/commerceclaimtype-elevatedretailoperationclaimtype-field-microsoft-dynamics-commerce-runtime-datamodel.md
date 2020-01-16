---
title: CommerceClaimType.ElevatedRetailOperationClaimType Field (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ElevatedRetailOperationClaimType Field
ms:assetid: F:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceClaimType.ElevatedRetailOperationClaimType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceclaimtype.elevatedretailoperationclaimtype(v=AX.60)
ms:contentKeyID: 62213208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceClaimType.ElevatedRetailOperationClaimType
dev_langs:
- CSharp
- C++
- VB
---

# ElevatedRetailOperationClaimType Field

Retail Operation Id Claim - used when manager override (elevation) is in effect to prevent unauthorized elevated operations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Shared ReadOnly ElevatedRetailOperationClaimType As String
'Usage
Dim value As String

value = CommerceClaimType.ElevatedRetailOperationClaimType
```

``` csharp
[DataMemberAttribute]
public static readonly string ElevatedRetailOperationClaimType
```

``` c++
[DataMemberAttribute]
public:
static initonly String^ ElevatedRetailOperationClaimType
```

## See Also

#### Reference

[CommerceClaimType Class](commerceclaimtype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

