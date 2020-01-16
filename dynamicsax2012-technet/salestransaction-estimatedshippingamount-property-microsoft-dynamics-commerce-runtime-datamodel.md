---
title: SalesTransaction.EstimatedShippingAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EstimatedShippingAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.EstimatedShippingAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.estimatedshippingamount(v=AX.60)
ms:contentKeyID: 65320342
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.EstimatedShippingAmount
dev_langs:
- CSharp
- C++
- VB
---

# EstimatedShippingAmount Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ESTIMATEDSHIPPINGAMOUNT")> _
<DataMemberAttribute> _
Public Property EstimatedShippingAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Nullable(Of Decimal)

value = instance.EstimatedShippingAmount

instance.EstimatedShippingAmount = value
```

``` csharp
[ColumnAttribute("ESTIMATEDSHIPPINGAMOUNT")]
[DataMemberAttribute]
public Nullable<decimal> EstimatedShippingAmount { get; set; }
```

``` c++
[ColumnAttribute(L"ESTIMATEDSHIPPINGAMOUNT")]
[DataMemberAttribute]
public:
property Nullable<Decimal> EstimatedShippingAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

