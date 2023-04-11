---
title: SalesTransactionData.IsSuspended Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSuspended Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.IsSuspended
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.issuspended(v=AX.60)
ms:contentKeyID: 62212590
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.IsSuspended
dev_langs:
- CSharp
- C++
- VB
---

# IsSuspended Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the transaction has been suspended.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISSUSPENDED")> _
<IgnoreDataMemberAttribute> _
Public Property IsSuspended As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As Boolean

value = instance.IsSuspended

instance.IsSuspended = value
```

``` csharp
[ColumnAttribute("ISSUSPENDED")]
[IgnoreDataMemberAttribute]
public bool IsSuspended { get; set; }
```

``` c++
[ColumnAttribute(L"ISSUSPENDED")]
[IgnoreDataMemberAttribute]
public:
property bool IsSuspended {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

