---
title: CardTypeInfo.CashBackLimit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashBackLimit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CashBackLimit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.cashbacklimit(v=AX.60)
ms:contentKeyID: 62209908
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CashBackLimit
dev_langs:
- CSharp
- C++
- VB
---

# CashBackLimit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash back limit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CASHBACKLIMIT")> _
Public Property CashBackLimit As Decimal
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As Decimal

value = instance.CashBackLimit

instance.CashBackLimit = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CASHBACKLIMIT")]
public decimal CashBackLimit { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CASHBACKLIMIT")]
public:
property Decimal CashBackLimit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

