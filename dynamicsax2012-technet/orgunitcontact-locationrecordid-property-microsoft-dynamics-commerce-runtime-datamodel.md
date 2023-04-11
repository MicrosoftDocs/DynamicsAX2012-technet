---
title: OrgUnitContact.LocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.LocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitcontact.locationrecordid(v=AX.60)
ms:contentKeyID: 62204943
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitContact.LocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LocationRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the locator record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property LocationRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As OrgUnitContact
Dim value As Long

value = instance.LocationRecordId
```

``` csharp
public long LocationRecordId { get; internal set; }
```

``` c++
public:
property long long LocationRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitContact Class](orgunitcontact-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

