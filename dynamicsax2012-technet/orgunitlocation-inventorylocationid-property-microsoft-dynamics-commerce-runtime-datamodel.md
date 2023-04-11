---
title: OrgUnitLocation.InventoryLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.InventoryLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.inventorylocationid(v=AX.60)
ms:contentKeyID: 62203194
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.InventoryLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTLOCATION")> _
Public Property InventoryLocationId As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.InventoryLocationId

instance.InventoryLocationId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTLOCATION")]
public string InventoryLocationId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTLOCATION")]
public:
property String^ InventoryLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

