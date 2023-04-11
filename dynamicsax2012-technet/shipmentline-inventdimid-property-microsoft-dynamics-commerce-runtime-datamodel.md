---
title: ShipmentLine.InventDimId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventDimId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.InventDimId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentline.inventdimid(v=AX.60)
ms:contentKeyID: 49854391
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.InventDimId
dev_langs:
- CSharp
- C++
- VB
---

# InventDimId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the variant information of the item being packed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTDIMID")> _
Public Property InventDimId As String
    Get
    Set
'Usage
Dim instance As ShipmentLine
Dim value As String

value = instance.InventDimId

instance.InventDimId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTDIMID")]
public string InventDimId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTDIMID")]
public:
property String^ InventDimId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The invent dim identifier.  

## See Also

#### Reference

[ShipmentLine Class](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

