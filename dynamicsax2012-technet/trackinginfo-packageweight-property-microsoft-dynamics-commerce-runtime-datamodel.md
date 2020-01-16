---
title: TrackingInfo.PackageWeight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PackageWeight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.PackageWeight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.packageweight(v=AX.60)
ms:contentKeyID: 49848726
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.PackageWeight
dev_langs:
- CSharp
- C++
- VB
---

# PackageWeight Property

Gets or sets the package weight.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PackageWeight As Weight
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Weight

value = instance.PackageWeight

instance.PackageWeight = value
```

``` csharp
[DataMemberAttribute]
public Weight PackageWeight { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Weight^ PackageWeight {
    Weight^ get ();
    void set (Weight^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Weight](weight-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The package weight.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

