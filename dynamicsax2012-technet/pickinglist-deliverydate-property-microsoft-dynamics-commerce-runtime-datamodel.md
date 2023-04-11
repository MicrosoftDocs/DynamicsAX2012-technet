---
title: PickingList.DeliveryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.DeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglist.deliverydate(v=AX.60)
ms:contentKeyID: 62210335
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.DeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the delivery date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As PickingList
Dim value As DateTimeOffset

value = instance.DeliveryDate

instance.DeliveryDate = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset DeliveryDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset DeliveryDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[PickingList Class](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

