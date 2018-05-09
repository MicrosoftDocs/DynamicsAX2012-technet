---
title: PurchaseOrderLine.QuantityOrdered Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityOrdered Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.QuantityOrdered
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.quantityordered(v=AX.60)
ms:contentKeyID: 62206928
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.QuantityOrdered
dev_langs:
- CSharp
- C++
- VB
---

# QuantityOrdered Property

Gets or sets the quantity ordered.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QUANTITYORDERED")> _
<DataMemberAttribute> _
Public Property QuantityOrdered As Decimal
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As Decimal

value = instance.QuantityOrdered

instance.QuantityOrdered = value
```

``` csharp
[ColumnAttribute("QUANTITYORDERED")]
[DataMemberAttribute]
public decimal QuantityOrdered { get; set; }
```

``` c++
[ColumnAttribute(L"QUANTITYORDERED")]
[DataMemberAttribute]
public:
property Decimal QuantityOrdered {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrderLine Class](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

