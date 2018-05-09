---
title: ChargeConfiguration.ToAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ToAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.toamount(v=AX.60)
ms:contentKeyID: 49840956
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ToAmount
dev_langs:
- CSharp
- C++
- VB
---

# ToAmount Property

Gets or sets the upper net amount threshold for Fixed transaction charges.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOAMOUNT")> _
<DataMemberAttribute> _
Public Property ToAmount As Decimal
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As Decimal

value = instance.ToAmount

instance.ToAmount = value
```

``` csharp
[ColumnAttribute("TOAMOUNT")]
[DataMemberAttribute]
public decimal ToAmount { get; set; }
```

``` c++
[ColumnAttribute(L"TOAMOUNT")]
[DataMemberAttribute]
public:
property Decimal ToAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

A value of 0 indicates that there is no upper bound.

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

