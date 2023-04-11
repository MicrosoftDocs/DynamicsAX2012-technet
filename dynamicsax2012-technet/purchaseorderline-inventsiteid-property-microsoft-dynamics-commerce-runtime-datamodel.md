---
title: PurchaseOrderLine.InventSiteId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventSiteId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventSiteId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.purchaseorderline.inventsiteid(v=AX.60)
ms:contentKeyID: 62208554
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrderLine.InventSiteId
dev_langs:
- CSharp
- C++
- VB
---

# InventSiteId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory site identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTSITEID")> _
Public Property InventSiteId As String
    Get
    Set
'Usage
Dim instance As PurchaseOrderLine
Dim value As String

value = instance.InventSiteId

instance.InventSiteId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTSITEID")]
public string InventSiteId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTSITEID")]
public:
property String^ InventSiteId {
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

