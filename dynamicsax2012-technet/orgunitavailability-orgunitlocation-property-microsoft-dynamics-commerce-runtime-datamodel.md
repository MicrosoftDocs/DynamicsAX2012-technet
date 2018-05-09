---
title: OrgUnitAvailability.OrgUnitLocation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitLocation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitAvailability.OrgUnitLocation
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitavailability.orgunitlocation(v=AX.60)
ms:contentKeyID: 62213111
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitAvailability.OrgUnitLocation
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitLocation Property

Gets or sets the instance of OrgUnitLocation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrgUnitLocation As OrgUnitLocation
    Get
    Set
'Usage
Dim instance As OrgUnitAvailability
Dim value As OrgUnitLocation

value = instance.OrgUnitLocation

instance.OrgUnitLocation = value
```

``` csharp
[DataMemberAttribute]
public OrgUnitLocation OrgUnitLocation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property OrgUnitLocation^ OrgUnitLocation {
    OrgUnitLocation^ get ();
    void set (OrgUnitLocation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OrgUnitAvailability Class](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

