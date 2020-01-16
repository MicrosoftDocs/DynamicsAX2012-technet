---
title: SalesTransaction.SalesPaymentDifference Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesPaymentDifference Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.SalesPaymentDifference
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.salespaymentdifference(v=AX.60)
ms:contentKeyID: 65321699
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.SalesPaymentDifference
dev_langs:
- CSharp
- C++
- VB
---

# SalesPaymentDifference Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESPAYMENTDIFFERENCE")> _
<DataMemberAttribute> _
Public Property SalesPaymentDifference As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.SalesPaymentDifference

instance.SalesPaymentDifference = value
```

``` csharp
[ColumnAttribute("SALESPAYMENTDIFFERENCE")]
[DataMemberAttribute]
public decimal SalesPaymentDifference { get; set; }
```

``` c++
[ColumnAttribute(L"SALESPAYMENTDIFFERENCE")]
[DataMemberAttribute]
public:
property Decimal SalesPaymentDifference {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

