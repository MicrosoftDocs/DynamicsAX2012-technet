---
title: ChargeConfiguration.FromAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.FromAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.fromamount(v=AX.60)
ms:contentKeyID: 49825750
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.FromAmount
dev_langs:
- CSharp
- C++
- VB
---

# FromAmount Property

Gets or sets the lower net amount threshold for Fixed transaction charges.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FROMAMOUNT")> _
<DataMemberAttribute> _
Public Property FromAmount As Decimal
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As Decimal

value = instance.FromAmount

instance.FromAmount = value
```

``` csharp
[ColumnAttribute("FROMAMOUNT")]
[DataMemberAttribute]
public decimal FromAmount { get; set; }
```

``` c++
[ColumnAttribute(L"FROMAMOUNT")]
[DataMemberAttribute]
public:
property Decimal FromAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

