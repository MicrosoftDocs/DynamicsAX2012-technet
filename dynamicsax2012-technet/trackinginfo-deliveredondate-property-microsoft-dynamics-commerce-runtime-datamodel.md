---
title: TrackingInfo.DeliveredOnDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveredOnDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.DeliveredOnDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.deliveredondate(v=AX.60)
ms:contentKeyID: 49825826
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.DeliveredOnDate
dev_langs:
- CSharp
- C++
- VB
---

# DeliveredOnDate Property

Gets or sets the delivered on date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveredOnDate As Nullable(Of DateTime)
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Nullable(Of DateTime)

value = instance.DeliveredOnDate

instance.DeliveredOnDate = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTime> DeliveredOnDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTime> DeliveredOnDate {
    Nullable<DateTime> get ();
    void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))\>  
The delivered on.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

