---
title: TransferOrder.ShipDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.ShipDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transferorder.shipdate(v=AX.60)
ms:contentKeyID: 62214217
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.ShipDate
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
<DataMemberAttribute> _
Public Property ShipDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As TransferOrder
Dim value As DateTimeOffset

value = instance.ShipDate

instance.ShipDate = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset ShipDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset ShipDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrder Class](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

