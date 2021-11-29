---
title: SalesTransaction.IsSales Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSales Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsSales
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.issales(v=AX.60)
ms:contentKeyID: 62215001
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsSales
dev_langs:
- CSharp
- C++
- VB
---

# IsSales Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether transaction type is of sales.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsSales As Boolean
    Get
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.IsSales
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsSales { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsSales {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

