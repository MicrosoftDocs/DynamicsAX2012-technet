---
title: PriceAdjustment.ValidationPeriodId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidationPeriodId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ValidationPeriodId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.validationperiodid(v=AX.60)
ms:contentKeyID: 49838282
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ValidationPeriodId
dev_langs:
- CSharp
- C++
- VB
---

# ValidationPeriodId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the validation period Id if using advanced date validation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VALIDATIONPERIODID")> _
Public Property ValidationPeriodId As String
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As String

value = instance.ValidationPeriodId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VALIDATIONPERIODID")]
public string ValidationPeriodId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VALIDATIONPERIODID")]
public:
property String^ ValidationPeriodId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

