---
title: InventoryNotFoundNotification.SalesLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.InventoryNotFoundNotification.SalesLineId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.inventorynotfoundnotification.saleslineid(v=AX.60)
ms:contentKeyID: 65320570
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.InventoryNotFoundNotification.SalesLineId
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineId Property

Gets the sales line identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLineId As String
    Get
    Private Set
'Usage
Dim instance As InventoryNotFoundNotification
Dim value As String

value = instance.SalesLineId
```

``` csharp
[DataMemberAttribute]
public string SalesLineId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SalesLineId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[InventoryNotFoundNotification Class](inventorynotfoundnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

