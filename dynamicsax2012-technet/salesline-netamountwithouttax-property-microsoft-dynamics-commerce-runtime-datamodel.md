---
title: SalesLine.NetAmountWithoutTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmountWithoutTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.NetAmountWithoutTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.netamountwithouttax(v=AX.60)
ms:contentKeyID: 65321850
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.NetAmountWithoutTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithoutTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NETAMOUNTWITHOUTTAX")> _
Public Property NetAmountWithoutTax As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.NetAmountWithoutTax

instance.NetAmountWithoutTax = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NETAMOUNTWITHOUTTAX")]
public decimal NetAmountWithoutTax { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NETAMOUNTWITHOUTTAX")]
public:
property Decimal NetAmountWithoutTax {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

