---
title: TrackingInfo.EstimatedDeliveryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EstimatedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.EstimatedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.estimateddeliverydate(v=AX.60)
ms:contentKeyID: 49847849
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.EstimatedDeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# EstimatedDeliveryDate Property

Gets or sets the estimated delivery date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EstimatedDeliveryDate As Nullable(Of DateTime)
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Nullable(Of DateTime)

value = instance.EstimatedDeliveryDate

instance.EstimatedDeliveryDate = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTime> EstimatedDeliveryDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTime> EstimatedDeliveryDate {
    Nullable<DateTime> get ();
    void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  
The estimated delivery date.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

