---
title: PriceAdjustment.DateValidationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateValidationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.DateValidationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.datevalidationtype(v=AX.60)
ms:contentKeyID: 49835790
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.DateValidationType
dev_langs:
- CSharp
- C++
- VB
---

# DateValidationType Property

Gets the date validation type (standard or advanced) for the price adjustment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DATEVALIDATIONTYPE")> _
Public Property DateValidationType As Integer
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As Integer

value = instance.DateValidationType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DATEVALIDATIONTYPE")]
public int DateValidationType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DATEVALIDATIONTYPE")]
public:
property int DateValidationType {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

