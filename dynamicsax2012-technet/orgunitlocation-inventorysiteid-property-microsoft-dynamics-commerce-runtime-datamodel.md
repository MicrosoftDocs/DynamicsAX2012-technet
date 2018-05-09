---
title: OrgUnitLocation.InventorySiteId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventorySiteId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.InventorySiteId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.inventorysiteid(v=AX.60)
ms:contentKeyID: 62210334
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.InventorySiteId
dev_langs:
- CSharp
- C++
- VB
---

# InventorySiteId Property

Gets or sets the inventory site identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSITEID")> _
<DataMemberAttribute> _
Public Property InventorySiteId As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.InventorySiteId

instance.InventorySiteId = value
```

``` csharp
[ColumnAttribute("INVENTSITEID")]
[DataMemberAttribute]
public string InventorySiteId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSITEID")]
[DataMemberAttribute]
public:
property String^ InventorySiteId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

