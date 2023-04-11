---
title: Shipment.CarrierId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CarrierId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.CarrierId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.carrierid(v=AX.60)
ms:contentKeyID: 62209852
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.CarrierId
dev_langs:
- CSharp
- C++
- VB
---

# CarrierId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the carrier id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SHIPCARRIERID")> _
Public Property CarrierId As String
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As String

value = instance.CarrierId

instance.CarrierId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SHIPCARRIERID")]
public string CarrierId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SHIPCARRIERID")]
public:
property String^ CarrierId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The carrier id related to this shipment.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

