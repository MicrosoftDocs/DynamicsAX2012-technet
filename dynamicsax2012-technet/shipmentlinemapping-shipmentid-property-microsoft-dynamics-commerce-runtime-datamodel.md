---
title: ShipmentLineMapping.ShipmentId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.ShipmentId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentlinemapping.shipmentid(v=AX.60)
ms:contentKeyID: 62209352
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.ShipmentId
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the packing slip id related to this mapping.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PACKINGSLIPID")> _
<DataMemberAttribute> _
Public Property ShipmentId As String
    Get
    Set
'Usage
Dim instance As ShipmentLineMapping
Dim value As String

value = instance.ShipmentId

instance.ShipmentId = value
```

``` csharp
[ColumnAttribute("PACKINGSLIPID")]
[DataMemberAttribute]
public string ShipmentId { get; set; }
```

``` c++
[ColumnAttribute(L"PACKINGSLIPID")]
[DataMemberAttribute]
public:
property String^ ShipmentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShipmentLineMapping Class](shipmentlinemapping-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

