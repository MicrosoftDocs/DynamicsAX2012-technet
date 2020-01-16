---
title: ChargeLine.ToAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ToAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.toamount(v=AX.60)
ms:contentKeyID: 62212084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ToAmount
dev_langs:
- CSharp
- C++
- VB
---

# ToAmount Property

Gets or sets To Amount of the charge.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ToAmount As Decimal
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Decimal

value = instance.ToAmount

instance.ToAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal ToAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ToAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

To Amount for defining tiered charges.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

