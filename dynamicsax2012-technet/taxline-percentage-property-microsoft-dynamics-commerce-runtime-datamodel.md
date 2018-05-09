---
title: TaxLine.Percentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Percentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLine.Percentage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxline.percentage(v=AX.60)
ms:contentKeyID: 49835404
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLine.Percentage
dev_langs:
- CSharp
- C++
- VB
---

# Percentage Property

Gets or sets the tax percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Percentage As Decimal
    Get
    Set
'Usage
Dim instance As TaxLine
Dim value As Decimal

value = instance.Percentage

instance.Percentage = value
```

``` csharp
[DataMemberAttribute]
public decimal Percentage { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Percentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxLine Class](taxline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

