---
title: TrackingInfo.PackagingType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PackagingType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.PackagingType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.packagingtype(v=AX.60)
ms:contentKeyID: 49831358
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.PackagingType
dev_langs:
- CSharp
- C++
- VB
---

# PackagingType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the packaging.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PackagingType As String
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As String

value = instance.PackagingType

instance.PackagingType = value
```

``` csharp
[DataMemberAttribute]
public string PackagingType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PackagingType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The type of the packaging.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

