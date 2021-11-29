---
title: PurchaseOrder.OrderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder.OrderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorder.orderlines(v=AX.60)
ms:contentKeyID: 62209332
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder.OrderLines
dev_langs:
- CSharp
- C++
- VB
---

# OrderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the purchase order lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderLines As ICollection(Of PurchaseOrderLine)
    Get
    Set
'Usage
Dim instance As PurchaseOrder
Dim value As ICollection(Of PurchaseOrderLine)

value = instance.OrderLines

instance.OrderLines = value
```

``` csharp
[DataMemberAttribute]
public ICollection<PurchaseOrderLine> OrderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<PurchaseOrderLine^>^ OrderLines {
    ICollection<PurchaseOrderLine^>^ get ();
    void set (ICollection<PurchaseOrderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[PurchaseOrderLine](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrder Class](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

