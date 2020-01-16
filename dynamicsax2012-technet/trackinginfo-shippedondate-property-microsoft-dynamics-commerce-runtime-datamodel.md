---
title: TrackingInfo.ShippedOnDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShippedOnDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ShippedOnDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.shippedondate(v=AX.60)
ms:contentKeyID: 49840378
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ShippedOnDate
dev_langs:
- CSharp
- C++
- VB
---

# ShippedOnDate Property

Gets or sets the shipped on date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippedOnDate As Nullable(Of DateTime)
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Nullable(Of DateTime)

value = instance.ShippedOnDate

instance.ShippedOnDate = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTime> ShippedOnDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTime> ShippedOnDate {
    Nullable<DateTime> get ();
    void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  
The shipped on.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

