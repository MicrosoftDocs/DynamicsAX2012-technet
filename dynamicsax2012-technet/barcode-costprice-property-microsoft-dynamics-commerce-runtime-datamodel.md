---
title: Barcode.CostPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CostPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.CostPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.costprice(v=AX.60)
ms:contentKeyID: 62207957
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.CostPrice
dev_langs:
- CSharp
- C++
- VB
---

# CostPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CostPrice As Decimal
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Decimal

value = instance.CostPrice

instance.CostPrice = value
```

``` csharp
[DataMemberAttribute]
public decimal CostPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal CostPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

