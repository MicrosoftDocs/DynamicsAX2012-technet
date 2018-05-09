---
title: Shipment.ShipDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.ShipDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.shipdate(v=AX.60)
ms:contentKeyID: 49841030
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.ShipDate
dev_langs:
- CSharp
- C++
- VB
---

# ShipDate Property

Gets or sets the ship date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SHIPDATE")> _
<DataMemberAttribute> _
Public Property ShipDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As DateTimeOffset

value = instance.ShipDate

instance.ShipDate = value
```

``` csharp
[ColumnAttribute("SHIPDATE")]
[DataMemberAttribute]
public DateTimeOffset ShipDate { get; set; }
```

``` c++
[ColumnAttribute(L"SHIPDATE")]
[DataMemberAttribute]
public:
property DateTimeOffset ShipDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
The ship date.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

