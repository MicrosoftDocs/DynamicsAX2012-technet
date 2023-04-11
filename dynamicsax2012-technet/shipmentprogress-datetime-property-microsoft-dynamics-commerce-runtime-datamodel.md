---
title: ShipmentProgress.DateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentProgress.DateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentprogress.datetime(v=AX.60)
ms:contentKeyID: 49833843
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentProgress.DateTime
dev_langs:
- CSharp
- C++
- VB
---

# DateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DateTime As Nullable(Of DateTime)
    Get
    Set
'Usage
Dim instance As ShipmentProgress
Dim value As Nullable(Of DateTime)

value = instance.DateTime

instance.DateTime = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTime> DateTime { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTime> DateTime {
    Nullable<DateTime> get ();
    void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  
The date time.  

## See Also

#### Reference

[ShipmentProgress Class](shipmentprogress-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

