---
title: ChargeLine.CalculatedAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CalculatedAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.CalculatedAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.calculatedamount(v=AX.60)
ms:contentKeyID: 49839146
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.CalculatedAmount
dev_langs:
- CSharp
- C++
- VB
---

# CalculatedAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the computed charge amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CALCULATEDAMOUNT")> _
Public Property CalculatedAmount As Decimal
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Decimal

value = instance.CalculatedAmount

instance.CalculatedAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CALCULATEDAMOUNT")]
public decimal CalculatedAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CALCULATEDAMOUNT")]
public:
property Decimal CalculatedAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The calculated amount.  

## Remarks

This amount is the actual computed amount for the charge line. It does not necessary map to the configuration.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

