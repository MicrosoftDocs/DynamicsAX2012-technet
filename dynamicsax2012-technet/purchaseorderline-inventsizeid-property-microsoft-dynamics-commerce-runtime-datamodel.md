---
title: PurchaseOrderLine.InventSizeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventSizeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventSizeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.inventsizeid(v=AX.60)
ms:contentKeyID: 62213006
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventSizeId
dev_langs:
- CSharp
- C++
- VB
---

# InventSizeId Property

Gets or sets the inventory size identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSIZEID")> _
<DataMemberAttribute> _
Public Property InventSizeId As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.InventSizeId

instance.InventSizeId = value
```

``` csharp
[ColumnAttribute("INVENTSIZEID")]
[DataMemberAttribute]
public string InventSizeId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSIZEID")]
[DataMemberAttribute]
public:
property String^ InventSizeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrderLine Class](purchaseorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

