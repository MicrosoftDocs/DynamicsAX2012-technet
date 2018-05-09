---
title: SalesTransaction.IsDepositOverridden Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDepositOverridden Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsDepositOverridden
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.isdepositoverridden(v=AX.60)
ms:contentKeyID: 62209769
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsDepositOverridden
dev_langs:
- CSharp
- C++
- VB
---

# IsDepositOverridden Property

Gets a value indicating whether the deposit amount was overridden.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsDepositOverridden As Boolean
    Get
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.IsDepositOverridden
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsDepositOverridden { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsDepositOverridden {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

