---
title: ShipmentLine.ShipmentLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.ShipmentLineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentline.shipmentlineid(v=AX.60)
ms:contentKeyID: 49836464
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.ShipmentLineId
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentLineId Property

Gets or sets the shipment line identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINENUM")> _
<DataMemberAttribute> _
Public Property ShipmentLineId As String
    Get
    Set
'Usage
Dim instance As ShipmentLine
Dim value As String

value = instance.ShipmentLineId

instance.ShipmentLineId = value
```

``` csharp
[ColumnAttribute("LINENUM")]
[DataMemberAttribute]
public string ShipmentLineId { get; set; }
```

``` c++
[ColumnAttribute(L"LINENUM")]
[DataMemberAttribute]
public:
property String^ ShipmentLineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The shipment line identifier.  

## See Also

#### Reference

[ShipmentLine Class](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

