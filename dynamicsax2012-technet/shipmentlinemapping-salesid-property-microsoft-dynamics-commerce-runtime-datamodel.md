---
title: ShipmentLineMapping.SalesId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.SalesId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentlinemapping.salesid(v=AX.60)
ms:contentKeyID: 62215216
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.SalesId
dev_langs:
- CSharp
- C++
- VB
---

# SalesId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales id related to this mapping.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESID")> _
<DataMemberAttribute> _
Public Property SalesId As String
    Get
    Set
'Usage
Dim instance As ShipmentLineMapping
Dim value As String

value = instance.SalesId

instance.SalesId = value
```

``` csharp
[ColumnAttribute("SALESID")]
[DataMemberAttribute]
public string SalesId { get; set; }
```

``` c++
[ColumnAttribute(L"SALESID")]
[DataMemberAttribute]
public:
property String^ SalesId {
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

