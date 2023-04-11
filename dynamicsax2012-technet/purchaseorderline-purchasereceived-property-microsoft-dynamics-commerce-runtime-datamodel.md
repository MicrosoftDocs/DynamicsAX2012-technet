---
title: PurchaseOrderLine.PurchaseReceived Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PurchaseReceived Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.PurchaseReceived
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.purchasereceived(v=AX.60)
ms:contentKeyID: 62209314
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.PurchaseReceived
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseReceived Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity received.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PURCHASERECEIVED")> _
Public Property PurchaseReceived As Decimal
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As Decimal

value = instance.PurchaseReceived

instance.PurchaseReceived = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PURCHASERECEIVED")]
public decimal PurchaseReceived { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PURCHASERECEIVED")]
public:
property Decimal PurchaseReceived {
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

