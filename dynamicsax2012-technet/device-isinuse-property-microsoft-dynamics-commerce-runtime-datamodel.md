---
title: Device.IsInUse Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsInUse Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.IsInUse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.device.isinuse(v=AX.60)
ms:contentKeyID: 62212762
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.IsInUse
dev_langs:
- CSharp
- C++
- VB
---

# IsInUse Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the device has been setup.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsInUse As Boolean
    Get
'Usage
Dim instance As Device
Dim value As Boolean

value = instance.IsInUse
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsInUse { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsInUse {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

