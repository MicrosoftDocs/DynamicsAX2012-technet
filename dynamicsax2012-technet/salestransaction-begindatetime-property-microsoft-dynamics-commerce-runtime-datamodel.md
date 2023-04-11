---
title: SalesTransaction.BeginDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BeginDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.BeginDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.begindatetime(v=AX.60)
ms:contentKeyID: 49851772
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.BeginDateTime
dev_langs:
- CSharp
- C++
- VB
---

# BeginDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the start date and time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BEGINDATETIME")> _
<DataMemberAttribute> _
Public Property BeginDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As DateTimeOffset

value = instance.BeginDateTime

instance.BeginDateTime = value
```

``` csharp
[ColumnAttribute("BEGINDATETIME")]
[DataMemberAttribute]
public DateTimeOffset BeginDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"BEGINDATETIME")]
[DataMemberAttribute]
public:
property DateTimeOffset BeginDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

