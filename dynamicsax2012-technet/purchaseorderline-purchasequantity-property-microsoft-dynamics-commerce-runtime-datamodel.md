---
title: PurchaseOrderLine.PurchaseQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PurchaseQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.PurchaseQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.purchasequantity(v=AX.60)
ms:contentKeyID: 62206299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.PurchaseQuantity
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseQuantity Property

Gets or sets the purchase quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PURCHASEQUANTITY")> _
Public Property PurchaseQuantity As Decimal
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As Decimal

value = instance.PurchaseQuantity

instance.PurchaseQuantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PURCHASEQUANTITY")]
public decimal PurchaseQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PURCHASEQUANTITY")]
public:
property Decimal PurchaseQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrderLine Class](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

